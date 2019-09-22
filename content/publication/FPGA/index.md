---
title: "FPGA-based Distributed Edge Training of SVM"
authors:
- admin
- Yashwardhan Narawane
- Rabi Mahapatra
- Vivek Sarin
date: "2019-02-24T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In proceedings of the 27th *ACM/SIGDA International Symposium on Field Programmable Gate Arrays* 2019
publication_short: In *ACM FPGA*

abstract: Support Vector Machine (SVM) is a widely used supervised machine learning algorithm for classification. Training SVM is challenging due to high computational cost and memory requirements. More often such training is handled at back end servers leading to significant communication and energy overheads. This approach is unsuitable for edge analytics which is a growing trend with various IoT applications. Enabling efficient training on the edge requires a distributed computing approach that has negligible communication overhead and an energy-efficient hardware design to execute it. In this paper, we present a scalable FPGA-based design for distributed SVM training amenable for edge-based learning. Specifically, we implement a pipelined QRSVM IP logic on Xilinx Virtex UltraScale+ VU9P FPGA. Each synthesized IP core operates at 125 MHz with a power dissipation of 39 Watts. We evaluate the training time, parallel speedup, scalability, and energy efficiency of the proposed design on five SVM benchmarks on a multiple FPGA system comprising up to eight FPGA units. When compared with software implementation on the traditional embedded system edge processors like ARM Cortex-A15, the proposed FPGA implementation is around 3x to 24x faster and 2x to 8x more energy efficient on the above benchmarks.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: true

links:
#- name: Custom Link
# url: 
url_pdf: https://dl.acm.org/citation.cfm?id=3293954
url_code: ''
url_dataset: ''
url_poster: 'http://people.tamu.edu/~jyoti1991/Documents/FPGA19_Poster.pdf'
url_project: ''
url_slides: 'http://people.tamu.edu/~jyoti1991/Documents/FPGA19_adSlide.pdf'
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
