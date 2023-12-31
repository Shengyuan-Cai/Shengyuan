---
title: "Motor imagery decoding in the presence of distraction using graph
sequence neural networks"
authors:
- Shengyuan Cai
- Haoran Li
- Qiang Wu
- Ju Liu
- Yu Zhang

date: "2022-06-10T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-06-10T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Transactions on Neural Systems and Rehabilitation Engineering, 30*(1716-1726)"
publication_short: ""

abstract: In this study, we propose a graph sequence neural network (GSNN) to accurately decode patterns of motor imagery from electroencephalograms (EEGs) in the presence of distractions. GSNN aims to build subgraphs by exploiting biological topologies among brain regions to capture local and global relationships across characteristic channels. Specifically, we model the similarity between pairwise EEG channels by the adjacency matrix of the graph sequence neural network. In addition, we propose a node domain attention selection network in which the connection and sparsity of the adjacency matrix can be adjusted dynamically according to the EEG signals acquired from different subjects. Extensive experiments on the public Berlin-distraction dataset show that in most experimental settings, our model performs considerably better than the state-of-the-art models. Moreover, comparative experiments indicate that our proposed node domain attention selection network plays a crucial role in improving the sensibility and adaptability of the GSNN model. The results show that the GSNN algorithm obtained superior classification accuracy (The average value of Recall, Precision, and F-score were 80.44%, 81.07% and 80.54%) compared to the state-of-the-art models. Finally, in the process of extracting the intermediate results, the relationships between important brain regions and channels were revealed to different influences in distraction themes.


tags:
- Representation learning
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9795322


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  filename: journal-article/paper1.png
  focal_point: Smart
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
slides: example
---

