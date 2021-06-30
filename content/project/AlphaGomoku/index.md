---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "AlphaGomoku"
summary: "Reinforcement Learning based artificial intelligence to master the game of Gomoku"
authors: []
tags: []
categories: []
date: 2021-03-30T19:44:32+08:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

- Designed and implemented player-player/play-computer Gomoku(five-in-a-row) chess games with features such as timer, move undo/redo, etc., using **Pygame**.
- Modeled after DeepMind’s AlphaGo Zero, AlhpaGomoku implemented two artificial intelligence algorithms using **Monte Carlo tree search** and **minimax algorithm with alpha-beta pruning**, respectively.