---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Translation Model from PPG to ABP"
authors: [Xiyang Wu*, Rishikesan Kamaleswaran]
date: 2021-08-10T02:06:07-08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate:  2020-10-31T02:06:07-08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: ""

# Summary. An optional shortened abstract.
summary: "This project intends to develop the translation model that interprets non-invasive blood pressure measurement Photoplethysmography (PPG) into invasive measurement Arterial Blood Pressure (ABP). Several distinct approaches have been made to achieve this goal. The first approach uses generative model for time series translation, while another one extracts indirect measurements for PPG signal and investigate their co-relation with systolic and diastolic blood pressure extracted from ABP signal. Heart Rate Variability (HRV) analysis is also made to achieve an overall image of all kinds of blood pressure measurements."

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
 
url_pdf: 
url_code:
url_dataset:
url_poster:
url_project:
url_slides: 
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
This project intends to develop the translation model that interprets non-invasive blood pressure measurement Photoplethysmography (PPG) into invasive measurement Arterial Blood Pressure (ABP). Several distinct approaches have been made to achieve this goal. The first approach uses generative model for time series translation, while another one extracts indirect measurements for PPG signal and investigate their co-relation with systolic and diastolic blood pressure extracted from ABP signal. Heart Rate Variability (HRV) analysis is also made to achieve an overall image of all kinds of blood pressure measurements. My responsibility in this project covers:
 * Investigate the frontier of heart rate analysis and generative model for time series translation, pre-process Arterial Blood Pressure (ABP) and Photoplethysmography (PPG) signal in MIMIC-II waveform dataset
 * Implement several benchmarks for the translation task, including TCN, LSTM and autoencoder, analyzed the mechanism for each benchmark and the temporal correlation within time series
 * Extract indirect measurement for blood pressure from PPG signal, like Pulse Arrival Time (PAT) and Slope Transit Time (STT), investigate their co-relation with corresponding systolic and diastolic blood pressure extracted from ABP signal
 * Extract Heart Rate Variability (HRV) analysis for synchronized heart rate signal ABP, PPG and ECG through PhysioNet Cardiovascular Signal Toolbox
---
