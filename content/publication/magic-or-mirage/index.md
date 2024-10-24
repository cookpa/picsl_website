---
title: 'Deep Learning in Medical Image Registration: Magic or Mirage?'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - rohitjena
  - Deeksha Sethi
  - Pratik Chaudhari
  - jimgee

# Author notes (optional)
author_notes:

date: '2024-09-27T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-09-27T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Neural Information Processing Systems 2024*
publication_short: In *NeurIPS 2024*

abstract: Classical optimization and learning-based methods are the two reigning paradigms in deformable image registration. While optimization-based methods boast generalizability across modalities and robust performance, learning-based methods promise peak performance, incorporating weak supervision and amortized optimization. However, the exact conditions for either paradigm to perform well over the other are shrouded and not explicitly outlined in the existing literature. In this paper, we make an explicit correspondence between the mutual information of the distribution of per-pixel intensity and labels, and the performance of classical registration methods. This strong correlation hints to the fact that architectural designs in learning-based methods is unlikely to affect this correlation, and therefore, the performance of learning-based methods. This hypothesis is thoroughly validated with state-of-the-art classical and learning-based methods. However, learning-based methods with weak supervision can perform high-fidelity intensity and label registration, which is not possible with classical methods. Next, we show that this high-fidelity feature learning does not translate to invariance to domain shift, and learning-based methods are sensitive to such changes in the data distribution. Finally, we propose a general recipe to choose the best paradigm for a given registration problem, based on these observations.


# Summary. An optional shortened abstract.
summary: Pitting predictive deep learning and classical registration methods on unsupervised performance and out-of-distribution generalization.

tags:
  - Image Registration
  - Evaluation

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2408.05839'
url_code: 'https://github.com/rohitrango/Magic-or-Mirage'
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
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - image registration

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
