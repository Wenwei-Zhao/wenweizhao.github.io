---
title: "Understanding the Ineffectiveness of the Transfer Attack in Intrusion Detection System"
authors:
- Rui Duan, Wenwei Zhao, Zhengping Jay Luo, Ning Wang, Yao Liu, Zhuo Lu
#author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2024-02-24T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "Network Security Empowered by Artificial Intelligence"
publication_short: "Network Security Empowered by Artificial Intelligence"

abstract: Recent works have revealed that network traffic packet detection systems (intrusion detection) are vulnerable to adversarial examples (AEs), where attackers can create AEs to make the detection system predict wrong network activities. Existing attacks only add a small perturbation to revise the network packets to obtain a high attack effectiveness. However, these AEs are crafted based on the white-box setting. It is unclear if such AEs can transfer to other black-box models, which could involve more security concerns. Therefore, in this chapter, we aim to explore the properties of the AEs’ transferability. To further understand the effectiveness of transfer attacks in the network domain, we first review the existing network intrusion detection systems and build different well-trained models (e.g., with different parameters and structures). Then, we employ various existing attack methods to generate different AEs based on specific surrogate models. To explore the transferability of AEs, we use different AEs to interact with different well-trained models, in order to find the key insights of transfer attacks in the network. We find that transfer attacks have some common properties with white-box attacks, and these findings may inspire more effective transfer attacks in future works.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

#tags:
#- Source Themes
#featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://link.springer.com/chapter/10.1007/978-3-031-53510-9_4
#url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_dataset: ''
#url_poster: ''
#url_project: ''
#url_slides: ''
#url_source: ''
#url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

#{{% callout note %}}
#Create your slides in Markdown - click the *Slides* button to check out the #example.
#{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
