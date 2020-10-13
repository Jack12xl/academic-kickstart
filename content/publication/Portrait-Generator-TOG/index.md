---
title: "A Free Viewpoint Portrait Generator with Dynamic Styling"
authors:
- Anpei Chen
- Ruiyang Liu
- Ling Xie
- Jinyi Yu

date: "2020-07-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-12-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "In *2019 IEEE International Conference on Multimedia & Expo Workshops (ICMEW) 2019*"
publication_short: ""

abstract: Generating portrait images from a single latent space facing the problem of entangled attributes, making it difficult to explicitly adjust the generation on specific attributes, e.g., contour and viewpoint control or dynamic styling. Therefore, we propose to decompose the generation space into two subspaces: geometric and texture space. We first encode portrait scans with a semantic occupancy field (SOF), which represents semantic-embedded geometry structure and output free viewpoint semantic segmentation maps. Then we design a semantic instance wised(SIW) StyleGAN to regionally styling the segmentation map. We capture 664 3D portrait scans for our SOF training and use real capture photos(FFHQ[12] and CelebA-HQ[16]) for SIW StyleGAN training. Adequate experiments show that our representations enable appearance consistent shape, pose, regional styles controlling, achieve state-of-the-art results, and generalize well in various application scenarios.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- GAN

featured: true

links:
# - name: Custom Link
#   url: http://example.org
url_pdf: https://ieeexplore.ieee.org/document/8795054
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Proposed teaser.'
  focal_point: ""
  preview_only: true

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% alert note %}}
Click the *Slides* button above to demo Academic's Markdown slides feature.
{{% /alert %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/). -->
