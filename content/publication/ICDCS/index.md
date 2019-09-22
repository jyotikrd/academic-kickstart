---
title: "Distributed QR Decomposition Framework for Training Support Vector Machines"
authors:
- admin
- V. N. S. Prithvi Sakuru
- Vivek Sarin
- Rabi Mahapatra
date: "2017-06-5T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-09-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In proceedings of the 37th IEEE *International Conference on Distributed Computing Systems* 2017
publication_short: In *IEEE ICDCS*

abstract: Support Vector Machines (SVM) belong to a class of supervised machine learning algorithms with applications in classification and regression analysis. SVM training is modeled as a convex optimization problem that is computationally tedious and has large memory requirements. Specifically, it is a quadratic programming problem which scales rapidly with the training set size rather than the dimensionality of the feature space. In this work, we first present a novel QR decomposition framework (QRSVM) to efficiently model and solve a large scale SVM problem by capitalizing on low-rank representations of the full kernel matrix rather than solving the problem as a sequence of smaller sub-problems. The low-rank structure of the kernel matrix is leveraged to transform the dense matrix into one with a sparse and separable structure. The modified SVM problem requires significantly lesser memory and computation. Our approach scales linearly with the training set size which makes it applicable to large datasets. This motivates towards our another contribution; exploring a distributed QRSVM framework to solve large-scale SVM classification problems in parallel across a cluster of computing nodes. We also derive an optimal step size for fast convergence of the dual ascent method which is used to solve the quadratic programming problem.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: true

links:
#- name: Custom Link
# url: 
url_pdf: https://ieeexplore.ieee.org/document/7980018
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'http://people.tamu.edu/~jyoti1991/Documents/ICDCS17_Presentation_qrsvm.pdf'
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
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
