---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "iPLAN: Intent-Aware Planning in Heterogeneous Traffic via Distributed Multi-Agent Reinforcement Learning"
authors: [Xiyang Wu, Rohan Chandra, Tianrui Guan, Amrit Singh Bedi, Dinesh Manocha]
date: 2023-06-09T16:23:35-07:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2023-06-09T18:04:35-07:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "7th Annual Conference on Robot Learning (CoRL), Nov. 2023, Atlanta, GA"
publication_short: ""

abstract: ""

# Summary. An optional shortened abstract.
summary: "Accepted by CoRL 2023 with **Oral Presentation** (**Accept Rate 6.6%**), Received **Best Paper Award** at IROS 2023 MRS Workshop"

tags: []
categories: []
featured: True

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/pdf/2306.06236.pdf
url_code: https://github.com/wuxiyang1996/iPLAN
url_dataset:
url_poster: https://wuxiyang1996.github.io/publication/iPLAN-2023/IROS2023_Poster.pdf
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "featured.png"
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
Navigating safely and efficiently in dense and heterogeneous traffic scenarios is challenging for autonomous vehicles (AVs) due to their inability to infer the behaviors or intentions of nearby drivers. In this work, we introduce a distributed multi-agent reinforcement learning (MARL) algorithm for joint trajectory and intent prediction for autonomous vehicles in dense and heterogeneous environments. Our approach for intent-aware planning, iPLAN, allows agents to infer nearby drivers' intents solely from their local observations. We model an explicit representation of agents' private incentives: Behavioral Incentive for high-level decision-making strategy that sets planning sub-goals and Instant Incentive for low-level motion planning to execute sub-goals. Our approach enables agents to infer their opponents' behavior incentives and integrate this inferred information into their decision-making and motion-planning processes. We perform experiments on two simulation environments, Non-Cooperative Navigation and Heterogeneous Highway. In Heterogeneous Highway, results show that, compared with centralized training decentralized execution (CTDE) MARL baselines such as QMIX and MAPPO, our method yields a 4.3% and 38.4% higher episodic reward in mild and chaotic traffic, with 48.1% higher success rate and 80.6% longer survival time in chaotic traffic. We also compare with a decentralized training decentralized execution (DTDE) baseline IPPO and demonstrate a higher episodic reward of 12.7% and 6.3% in mild traffic and chaotic traffic, 25.3% higher success rate, and 13.7% longer survival time.
```
@inproceedings{wu2023intent, 
  title={Intent-Aware Planning in Heterogeneous Traffic via Distributed Multi-Agent Reinforcement Learning}, 
  author={Wu, Xiyang and Chandra, Rohan and Guan, Tianrui and Bedi, Amrit and Manocha, Dinesh}, 
  booktitle={7th Annual Conference on Robot Learning}, 
  year={2023}
```
