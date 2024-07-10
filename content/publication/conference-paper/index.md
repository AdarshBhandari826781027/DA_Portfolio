---
title: 'An Interpretable Image Denoising Framework via Dual Disentangled Representation Learning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2023-11-08T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Intelligent Vehicles* ( Volume-9, Issue-1, January 2024)
publication_short: In *ICW*

abstract: Various unfavorable conditions such as fog, snow, and rain may degrade image quality and pose tremendous threats to the safety of autonomous driving. Numerous image-denoising solutions have been proposed to improve visibility under adverse weather conditions. However, previous studies have been limited in robustness, generalization ability, and interpretability as they were designed for specific scenarios. To address this problem, we introduce an interpretable image-denoising framework via Dual Disentangled Representation Learning (DDRL) to enhance robustness and interpretability by decomposing an image into content factors (e.g., objects) and context factors (e.g., weather conditions). DDRL consists of two Disentangled Representation Learning (DRL) blocks. In each DRL block, an input image is deconstructed into the latent content distribution and the weather distribution by minimizing their mutual information. To mitigate the impacts of weather styles, we incorporated a content discriminator and adversarial objectives to learn the decomposable interaction between two DRL blocks. Furthermore, we standardized the weather feature space, enabling our method to apply to various downstream tasks such as diverse degraded image generation. We evaluated DDRL under three weather conditions including fog, rain, and snow. The experimental results demonstrate that DDRL shows competitive performance with good generalization capability and high robustness under numerous weather conditions. Furthermore, quantitative analysis shows that DDRL can capture interpretable variations of weather factors and decompose them for safe and reliable all-weather autonomous driving.

# Summary. An optional shortened abstract.
summary: Various unfavorable conditions such as fog, snow, and rain may degrade image quality and pose tremendous threats to the safety of autonomous driving. Numerous image-denoising solutions have been proposed to improve visibility under adverse weather conditions. However, previous studies have been limited in robustness, generalization ability, and interpretability as they were designed for specific scenarios. To address this problem, we introduce an interpretable image-denoising framework via Dual Disentangled Representation Learning (DDRL) to enhance robustness and interpretability by decomposing an image into content factors (e.g., objects) and context factors (e.g., weather conditions). DDRL consists of two Disentangled Representation Learning (DRL) blocks. In each DRL block, an input image is deconstructed into the latent content distribution and the weather distribution by minimizing their mutual information. To mitigate the impacts of weather styles, we incorporated a content discriminator and adversarial objectives to learn the decomposable interaction between two DRL blocks. Furthermore, we standardized the weather feature space, enabling our method to apply to various downstream tasks such as diverse degraded image generation. We evaluated DDRL under three weather conditions including fog, rain, and snow. The experimental results demonstrate that DDRL shows competitive performance with good generalization capability and high robustness under numerous weather conditions. Furthermore, quantitative analysis shows that DDRL can capture interpretable variations of weather factors and decompose them for safe and reliable all-weather autonomous driving.
tags:
  - Large Language Models

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_source: 'https://doi.org/10.1109/TIV.2023.3331017'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---
