---
title: "Can Machine Learning Be Better than Biased Readers?"
authors:
- admin
- Rui Zhu
- Pascal N.Tyrrell
author_notes:
- "Equal contribution"
- "Equal contribution"
date: "2023-04-28T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-04-28T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["Journal article"]

# Publication name and optional abbreviated publication name.
publication: "*Tomography*"
publication_short: ""

abstract: Training machine learning (ML) models in medical imaging requires large amounts of labeled data. To minimize labeling workload, it is common to divide training data among multiple readers for separate annotation without consensus and then combine the labeled data for training a ML model. This can lead to a biased training dataset and poor ML algorithm prediction performance. The purpose of this study is to determine if ML algorithms can overcome biases caused by multiple readers&rsquo; labeling without consensus. This study used a publicly available chest X-ray dataset of pediatric pneumonia. As an analogy to a practical dataset without labeling consensus among multiple readers, random and systematic errors were artificially added to the dataset to generate biased data for a binary-class classification task. The Resnet18-based convolutional neural network (CNN) was used as a baseline model. A Resnet18 model with a regularization term added as a loss function was utilized to examine for improvement in the baseline model. The effects of false positive labels, false negative labels, and random errors (5&ndash;25%) resulted in a loss of AUC (0&ndash;14%) when training a binary CNN classifier. The model with a regularized loss function improved the AUC (75&ndash;84%) over that of the baseline model (65&ndash;79%). This study indicated that it is possible for ML algorithms to overcome individual readers&rsquo; biases when consensus is not available. It is recommended to use regularized loss functions when allocating annotation tasks to multiple readers as they are easy to implement and effective in mitigating biased labels.

# Summary. An optional shortened abstract.
summary: Statistical analysis on readers' bias observed in medical imaging annotations for constructing machine learning models.

tags:
- Source Themes

featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://doi.org/10.3390/tomography9030074
url_code: 'https://github.com/7hestral/ImperfectGoldStandard'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/boy-in-blue-and-white-plaid-shirt-reading-book-v7FT5ngIEfA?utm_content=creditShareLink&utm_medium=referral&utm_source=unsplash)'
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
# slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
