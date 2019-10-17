---
title: "Isometry Aware Preconditioning for Mesh Parameterization"
authors:
- Sebastian Claici
- Mikhail Bessmeltsev
- Scott Schaefer
- Justin Solomon
date: "2017-07-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Symposium on Geometry Processing*
publication_short: In *SGP 2017*

abstract: This paper presents a new preconditioning technique for large-scale geometric optimization problems, inspired by applications in mesh parameterization. Our positive (semi-)definite preconditioner acts on the gradients of optimization problems whose variables are positions of the vertices of a triangle mesh in $\\mathbb{R}^2$ or of a tetrahedral mesh in $\\mathbb{R}^3$ , converting localized distortion gradients into the velocity of a globally near-rigid motion via a linear solve. We pose our preconditioning tool in terms of the Killing energy of a deformation field and provide new efficient formulas for constructing Killing operators on triangle and tetrahedral meshes. We demonstrate that our method is competitive with state-of-the-art algorithms for locally injective parameterization using a variety of optimization objectives and show applications to two- and three-dimensional mesh deformation.

tags:
- Source Themes
featured: true

links:
url_pdf: https://people.csail.mit.edu/jsolomon/assets/killing_param.pdf
url_code: https://github.com/sebastian-claici/AKVFParam

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ""
  preview_only: true

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
