---
title: "Multiview Vehicle Tracking by Graph Matching Model"
authors:
- Minye Wu
- Guli Zhang
- Ning Bi
- Ling Xie
- Yuanquan Hu 
- Zhiru Shi

date: "2019-05-14T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-05-14T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "The IEEE Conference on Computer Vision and Pattern Recognition (CVPR) Workshops, 2019, pp. 29-36"
publication_short: "CVPR 2019 workshop"

abstract: Using multiple visual cameras to sensing traffic, especially tracking of vehicles, is a challenging task because of the large number of vehicle models, non-overlapping views, occlusion, view change and time-consuming algorithms. All of them remain obstacles in real world deployment. In this work, we propose a novel and flexible vehicle tracking framework, which formulates matching problem as a graph matching problem and solve it from the bottom up. In our framework, many restrictions can be added into the graph uniformly and simply. Moreover, we introduced an iterative Graph Matching Solver algorithm which can divide and reduce the graph matching problem's scale efficiently. Additionally, We also take the advantage of geographic information and make a combination with deep ReID features, motion and temporal information. The result shows that our algorithm achieves a 9th place at the AI City Challenge 2019.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Tracking
- ReID

featured: false

links:
# - name: Custom Link
#   url: http://example.org
url_pdf: http://openaccess.thecvf.com/content_CVPRW_2019/papers/AI%20City/Wu_Multiview_Vehicle_Tracking_by_Graph_Matching_Model_CVPRW_2019_paper.pdf
# url_code: '#'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Matching pipeline. First, tracklets are generated from videos. Each small rectangle in the figure represents a tracklet instance. Each color represents a specific vehicle. T-Graphs are built from Tracklet sets of different intersections. Applying graph matching solver (GMS) on T-Graphs can obtain tracklet groups. Tracklet groups can build a G-Graph. Then the final result can be calculated by GMS.'
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
