---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "AlphaZero Chess Player"
summary: "The AlphaZero chess player is the course project for Robotic Intelligence: Planning in Gatech. The general idea of this project is to utilize the AlphaZero model that is derived from the Monte-Carlo Search Tree (MCTS) on the partially observable chess playing environment. To estimate the opponent status on the board since it's unavailale for the current player, the practicle filter on king tracking is incorporated with the AlphaZero model."
authors: []
tags: []
categories: []
date: 2020-11-24T10:26:10-08:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: "project/chess_mcts/mcts_report.pdf"
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
<img src="./sample_video.gif" title="AlphaZero Chess Player" width="450" height="450" />
The AlphaZero chess player is the course project for Robotic Intelligence: Planning in Gatech. The general idea of this project is to utilize the AlphaZero model that is derived from the Monte-Carlo Search Tree (MCTS) on the partially observable chess playing environment. To estimate the opponent status on the board since it's unavailale for the current player, the practicle filter on king tracking is incorporated with the AlphaZero model. My responsibility in this project covers: 
 * Regulate the fully and partially observable chess playing task, implement the vanilla Monte-Carlo Search Tree on the chess playing task
 * Implement the AlphaZero method by incorporating the neural network for state evaluation and decision making with the MCTS, implement the particle filter on the opponent's king tracking task to optimize the model
 * Integrate the modules for different tasks into the feasible agent, establish the training and testing framework, implement the chess player agent on the partially observable chess playing environment
---
