---
title: "Automated screening of computed tomography using weakly supervised anomaly detection"
authors:
- admin
- Michael D. Cusimano
- Alexander Bilbily
- Rahul G. Krishnan
- Pascal N. Tyrrell
date: "2023-05-29T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-05-29T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["Journal article"]

# Publication name and optional abbreviated publication name.
publication: "International Journal of Computer Assisted Radiology and Surgery"
publication_short: "IJCARS"

abstract: Background \n Current artificial intelligence studies for supporting CT screening tasks depend on either supervised learning or detecting anomalies. However, the former involves a heavy annotation workload owing to requiring many slice-wise annotations (ground truth labels); the latter is promising, but while it reduces the annotation workload, it often suffers from lower performance. This study presents a novel weakly supervised anomaly detection (WSAD) algorithm trained based on scan-wise normal and anomalous annotations to provide better performance than conventional methods while reducing annotation workload. \n Methods \n Based on surveillance video anomaly detection methodology, feature vectors representing each CT slice were trained on an AR-Net-based convolutional network using a dynamic multiple-instance learning loss and a center loss function. The following two publicly available CT datasets were retrospectively analyzed; the RSNA brain hemorrhage dataset (12,862 normal scans and 8882 scans with intracranial hematoma) and COVID-CT set (282 normal scans and 95 scans with COVID-19). \n Results \n Anomaly scores of each slice were successfully predicted despite inaccessibility to any slice-wise annotations. Slice-level area under the curve (AUC), sensitivity, specificity, and accuracy from the brain CT dataset were 0.89, 0.85, 0.78, and 0.79, respectively. The proposed method reduced the number of annotations in the brain dataset by 97.1% compared to an ordinary slice-level supervised learning method. \n Conclusion \n This study demonstrated a significant annotation reduction in identifying anomalous CT slices compared to a supervised learning approach. The effectiveness of the proposed WSAD algorithm was verified through higher AUC than existing anomaly detection techniques.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes

featured: true

links:
# - name: Custom Link
#   url: http://example.org
url_pdf: https://doi.org/10.1007/s11548-023-02965-4
url_code: 'https://github.com/hibiat/wsad.'
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

<!-- {{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
