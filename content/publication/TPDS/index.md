---
title: "Fast and Communication-Efficient Algorithm for Distributed Support Vector Machine Training"
authors:
- admin
- Vivek Sarin
- Rabi Mahapatra
date: "2018-11-07T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Transactions on Parallel and Distributed System*"
publication_short: In *IEEE TPDS*

abstract: Support Vector Machines (SVM) are widely used as supervised learning models to solve the classification problem in machine learning. Training SVMs for large datasets is an extremely challenging task due to excessive storage and computational requirements. To tackle so-called big data problems, one needs to design scalable distributed algorithms to parallelize the model training and to develop efficient implementations of these algorithms. In this paper, we propose a distributed algorithm for SVM training that is scalable and communication-efficient. The algorithm uses a compact representation of the kernel matrix, which is based on the QR decomposition of low-rank approximations, to reduce both computation and storage requirements for the training stage. This is accompanied by considerable reduction in communication required for a distributed implementation of the algorithm. Experiments on benchmark data sets with up to five million samples demonstrate negligible communication overhead and scalability on up to 64 cores. Execution times are vast improvements over other widely used packages. Furthermore, the proposed algorithm has linear time complexity with respect to the number of samples making it ideal for SVM training on decentralized environments such as smart embedded systems and edge-based internet of things, IoT.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

# links:
#- name: Custom Link
#  url:
url_pdf: http://ieeexplore.ieee.org/abstract/document/8526323
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ""   #'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
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

{{% alert note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}

