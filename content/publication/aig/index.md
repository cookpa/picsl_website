---
title: "Elucidating Optimal Reward-Diversity Tradeoffs in Text-to-Image Diffusion Models"
authors:
- rohitjena
- Ali Taghibakhshi
- Sahil Jain
- Gerald Shen
- Nima Tajbakhsh
- Arash Vahdat
date: "2024-09-06T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-09-06T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["preprint"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Text-to-image (T2I) diffusion models have become prominent tools for generating high-fidelity images from text prompts. However, when trained on unfiltered internet data, these models can produce unsafe, incorrect, or stylistically undesirable images that are not aligned with human preferences. To address this, recent approaches have incorporated human preference datasets to fine-tune T2I models or to optimize reward functions that capture these preferences. Although effective, these methods are vulnerable to reward hacking, where the model overfits to the reward function, leading to a loss of diversity in the generated images. In this paper, we prove the inevitability of reward hacking and study natural regularization techniques like KL divergence and LoRA scaling, and their limitations for diffusion models. We also introduce Annealed Importance Guidance (AIG), an inference-time regularization inspired by Annealed Importance Sampling, which retains the diversity of the base model while achieving Pareto-Optimal reward-diversity tradeoffs. Our experiments demonstrate the benefits of AIG for Stable Diffusion models, striking the optimal balance between reward optimization and image diversity. Furthermore, a user study confirms that AIG improves diversity and quality of generated images across different model architectures and reward functions.


# Summary. An optional shortened abstract.
summary: Inference-time regularization to achieve Pareto-Optimal reward-diversity tradeoffs in text-to-image diffusion models.

tags:
- Generative AI
- Text-to-Image Diffusion Models

featured: false

# links:
# - name: Custom Link
#   url: http://example.org
url_pdf: https://arxiv.org/pdf/2409.06493
url_code: 'https://github.com/NVIDIA/NeMo-Aligner'
# url_dataset: '#'
# url_poster: '#'
url_project: 'https://jenaroh.it/annealed-imp-guidance/'
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Teaser'
  focal_point: ""
  preview_only: false
  filename: teaser.png

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internship

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
