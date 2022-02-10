---
title: "Impacts of Image Obfuscation on Fine-grained Activity Recognition in Egocentric Video"
authors:
- Soroush Shahi
- Rawan Alharbi
- Yang Gao 
- Sougata Sen
- Aggelos K Katsaggelos
- Josiah Hester
- Nabil Alshurafa

date: "2022-03-21T00:02:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["0"]

# Publication name and optional abbreviated publication name.
publication: In 18th International Workshop on Context and Activity Modeling and Recognition (CoMoReA)
publication_short: In CoMoReA

abstract: Automated detection and validation of fine-grained human activities from egocentric vision has gained increased attention in recent years due to the rich information afforded by RGB images. However, it is not easy to discern how much rich information is necessary to detect the activity of interest reliably. Localization of hands and objects in the image has proven helpful to distinguishing between hand-related fine-grained activities. This paper describes the design of a hand-object-based mask obfuscation method (hobm) and assesses its effect on automated recognition of fine-grained human activities. hobm masks all pixels other than the hand and object in-hand, improving the protection of personal user information (PUI). We test a deep learning model trained with and without obfuscation using a public egocentric activity dataset with 86 class labels and achieve almost similar classification accuracies (2% decrease with obfuscation). Our findings show that it is possible to protect PUI at smaller image utility costs (loss of accuracy). 


# Summary. An optional shortened abstract.
summary: In this paper we assess the effect of hand-object-based obfuscation on recognizing fine-grained human activities.

tags:
- Source Themes
featured: true

links:
- name: Custom Link
  url: http://comorea.org
# url_pdf: '#'
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
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  # focal_point: ""
  # preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- external-collaboration

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides:
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).
 -->