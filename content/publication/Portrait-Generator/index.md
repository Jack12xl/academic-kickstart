
---
title: "A Free Viewpoint Portrait Generator with Dynamic Styling"
authors:
- Anpei Chen
- Ruiyang Liu
- Ling Xie
- Zhang Chen
- Hao Su
- Jingyi Yu

date: "2020-07-07T00:00:00Z"
doi: ""

publishDate: "2020-7-71T00:00:00Z"

math: true
diagram: true
image:
  caption: 'Image credit: [](./featured.png)'
  focal_point: ""
  placement: 2
  preview_only: false

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
#publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Transactions on Graphics Siggraph 2022"
publication_short: "Transactions on Graphics Siggraph 2022"



# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- GAN

featured: true

links:
# - name: Custom Link
#   url: http://example.org
url_pdf: https://dl.acm.org/doi/10.1145/3470848
url_code: https://github.com/apchenstu/sofgan
# url_dataset: '#'
# url_poster: '#'
url_project: ''
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

![](./pipeline.pdf)

### Abstract

Recently, GANs have been widely used for portrait generation. However, in the latent space learned by GANs, different attributes, such as pose, shape, and texture style, are generally entangled, making the explicit control of specific attributes difficult. To address this issue, we propose a SOFGAN image generator to decouple the latent space of portraits into a geometry space and a texture space. The latent codes sampled from the two subspaces are fed to two network branches separately, one to generate the 3D geometry of portraits with canonical pose, and the other to generate textures. The aligned 3D geometries also come with semantic part segmentation, encoded as a semantic occupancy field (SOF). The SOF allows the rendering of consistent 2D semantic segmentation maps at arbitrary views, which are then fused with the generated texture maps and stylized to a portrait photo using our semantic instance-wise (SIW) Module. Through extensive experiments, we show that our system can generate high quality portrait images with independently controllable geometry and texture attributes. The method also generalizes well in various applications such as appearance-consistent facial animation and dynamic styling.

### Motivation
![](./pipeline.gif)


<!-- {{% alert note %}}
Click the *Slides* button above to demo Academic's Markdown slides feature.
{{% /alert %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/). -->
