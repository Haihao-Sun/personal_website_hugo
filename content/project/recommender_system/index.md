---
title: Recommender System on Stream’s datasets
summary: Recommender System on Stream’s datasets
tags:
- Machine Learning
date: "2020-06-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

links:
- icon: github
  icon_pack: fab
  name: Follow
  url: https://github.com/TribbianniSun
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---



Built the recommender system based on Stream's video game review dataset (~200,000), with accuracy ranking 16th out of 401 (4%) on Kaggle

- Pre-processed the text data using stemming and lemmatization; designed the game category classifier by building a pipeline using Scikit-Learn’s CountVectorizer, TfidfTransformer, and linear SVM
- Predicted whether a user would play a specific game based on the popularity of the game and the Jaccard Similarity between users