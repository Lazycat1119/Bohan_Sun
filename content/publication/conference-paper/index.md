---
title: 'MCF-SVC'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2025-01-31T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2025-01-31T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['journal-article']

# Publication name and optional abbreviated publication name.
publication: Submitting to IEEE Signal Processing Letters
publication_short: In *ICW*

abstract: Singing voice conversion is to convert the source singing voice into the target singing voice except for the content.Currently, flow-based models can complete the task of voice conversion, but they struggle to effectively extract latent variables in the more rhythmically rich and emotionally expressive task of singing voice conversion, while also facing issues with low efficiency in voice processing. In this paper, we propose a high-fidelity flow-based model based on multi-condition feature constraints called MCF-SVC, which enhances the capture of voice details by integrating multiple latent attribute encoders. We also use Multi-stream inverse short-time Fourier transform(MS-iSTFT) instead of traditional vocoder to enhance the speed of voice reconstruction. We have compared the synthesized singing voice of our model with those of other competitive models from multiple dimensions, and our proposed model is highly consistent with the current state-of-the-art, with the demo which is available at https://lazycat1119.github.io/MCF-SVC-demo.

# Summary. An optional shortened abstract.
summary: Faced with the issues of slow singing voice conversion speed and low fidelity, we incorporated a HuBERT soft speech representation learning module into the VITS model (a mainstream TTS system). Additionally, we extracted the pitch (fundamental frequency, F0) and emotion of the speech as input conditions for the normalizing flow. We also added an iSTFT - based decoder to accelerate the waveform reconstruction speed.

tags:
  - Singing Voice Conversion

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'uploads/SPL.pdf'
url_code: 'https://lazycat1119.github.io/MCF-SVC-demo/'
#url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_poster: ''
#url_project: ''
#url_slides: ''
#url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  #caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

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

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
