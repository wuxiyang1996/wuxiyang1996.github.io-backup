---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Firecommander: An interactive, probabilistic multi-agent environment for joint perception-action tasks"
authors: [Esmaeil Seraj, Xiyang Wu, Matthew Gombolay]
date: 2020-10-31T16:23:35-07:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-10-31T16:23:35-07:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "arXiv:2011.00165"
publication_short: ""

abstract: ""

# Summary. An optional shortened abstract.
summary: "arXiv:2011.001653"

tags: []
categories: []
featured: False

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/pdf/2011.00165.pdf
url_code:
url_dataset:
url_poster:
url_project:
url_slides: https://wuxiyang1996.github.io/publication/FireCommander_2020/FireCommander2020_Xiyang_Wu.pdf
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
---
The purpose of this tutorial is to help individuals use the \underline{FireCommander} game environment for research applications. The FireCommander is an interactive, probabilistic joint perception-action reconnaissance environment in which a composite team of agents (e.g., robots) cooperate to fight dynamic, propagating firespots (e.g., targets). In FireCommander game, a team of agents must be tasked to optimally deal with a wildfire situation in an environment with propagating fire areas and some facilities such as houses, hospitals, power stations, etc. The team of agents can accomplish their mission by first sensing (e.g., estimating fire states), communicating the sensed fire-information among each other and then taking action to put the firespots out based on the sensed information (e.g., dropping water on estimated fire locations). The FireCommander environment can be useful for research topics spanning a wide range of applications from Reinforcement Learning (RL) and Learning from Demonstration (LfD), to Coordination, Psychology, Human-Robot Interaction (HRI) and Teaming. There are four important facets of the FireCommander environment that overall, create a non-trivial game: (1) Complex Objectives: Multi-objective Stochastic Environment, (2)Probabilistic Environment: Agents' actions result in probabilistic performance, (3) Hidden Targets: Partially Observable Environment and, (4) Uni-task Robots: Perception-only and Action-only agents. The FireCommander environment is first-of-its-kind in terms of including Perception-only and Action-only agents for coordination. It is a general multi-purpose game that can be useful in a variety of combinatorial optimization problems and stochastic games, such as applications of Reinforcement Learning (RL), Learning from Demonstration (LfD) and Inverse RL (iRL).
```
@misc{seraj2021firecommander,
      title={FireCommander: An Interactive, Probabilistic Multi-agent Environment for Heterogeneous Robot Teams}, 
      author={Esmaeil Seraj and Xiyang Wu and Matthew Gombolay},
      year={2021},
      eprint={2011.00165},
      archivePrefix={arXiv},
      primaryClass={cs.RO}
}
```
