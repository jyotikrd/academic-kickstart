---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "A Relaxed Synchronization Approach for Solving Parallel Quadratic Programming Problems with Guaranteed Convergence"
authors:
- Kooktae Li
- Raktim Bhattacharya
- Jyoitkrishna Dass
- V.N.S. Prithvi Sakuru
- Rabi Mahapatra
date: 2016-09-21T21:34:06-05:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In proceedings of the 30th IEEE *International Parallel and Distributed Processing Symposium* 2016
publication_short: In *IEEE IPDPS*

abstract: In this paper we present a novel numerical algorithm for efficiently solving large-scale quadratic programming problems in massively parallel computing systems. The main challenge in maximizing processor utilization is to reduce idling due to synchronization across processors. Typically, synchronization is necessary after every iteration, which prevents many numerical algorithms from scaling with number of processors. We relax this requirement by synchronizing at a lower rate, which is referred to as lazy synchronization. We show analytically and experimentally that lazy synchronization is numerically stable and converges to the same result as the conventional tightly synchronized implementation. Furthermore, the convergence speed of the proposed algorithm is faster with lazy synchronization. The numerical stability, convergence rate and the optimal rate for synchronization are analytically shown. The proposed algorithm is implemented in a 40-node distributed system in the Amazon Elastic Computing infrastructure. We show a 160 times speedup in solution time for a large-scale quadratic programming problem using a synthetic dataset. The experiments demonstrate that the use of relaxed synchronization technique reduces communication overhead in the distributed systems by 99.65% in comparison to the tightly synchronization implementation.

# Summary. An optional shortened abstract.
summary: ""

tags:
- Source Themes
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://ieeexplore.ieee.org/document/7516014
url_code:
url_dataset:
url_poster: http://people.tamu.edu/~jyoti1991/Documents/IPDPS16_Poster.pdf
url_project:
url_slides: http://people.tamu.edu/~jyoti1991/Documents/IPDPS2016_relaxed_sync.pdf
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
