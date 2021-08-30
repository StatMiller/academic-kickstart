---
title: "Accounting for Location Measurement Error in Imaging Data with Application to Atomic Resolution Images of Crystalline Materials"
authors:
- Matthew Miller
- Matthew Cabral
- Elizabeth Dickey
- James LeBeau
- Brian Reich
date: ""
doi: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Technometrics*
publication_short: In *Technometrics*

abstract: Scientists use imaging to identify objects of interest and infer properties of these objects. The locations of these objects are often measured with error, which when ignored leads to biased parameter estimates and inflated variance. Current measurement error methods require an estimate or knowledge of the measurement error variance to correct these estimates, which may not be available. Instead, we create a spatial Bayesian hierarchical model that treats the locations as parameters, using the image itself to incorporate positional uncertainty. We lower the computational burden by approximating the likelihood using a noncontiguous block design around the object locations. We use this model to quantify the relationship between the intensity and displacement of hundreds of atom columns in crystal structures directly imaged via scanning transmission electron microscopy (STEM). Atomic displacements are related to important phenomena such as piezoelectricity, a property useful for engineering applications like ultrasound. Quantifying the sign and magnitude of this relationship will help materials scientists more precisely design materials with improved piezoelectricity. A simulation study confirms our method corrects bias in the estimate of the parameter of interest and drastically improves coverage in high noise scenarios compared to non-measurement error models.

# Summary. An optional shortened abstract.
summary: A new measurement error model for image data applied to learning about atomic-scale material properties.

tags:
- Spatial Statistics
- Measurement Error Models
- Bayesian Hierarchical Modeling

featured: true

links:
url_pdf: 'https://arxiv.org/pdf/1910.14195.pdf'
url_code: 'https://github.com/StatMiller/HierarchicalSTEM'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
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

