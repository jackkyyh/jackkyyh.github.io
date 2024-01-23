---
title: Graphical CSS Code Transformation Using ZX Calculus

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Sarah Meng Li
- Lia Yeh
- Aleks Kissinger
- Michele Mosca
- Michael Vasmer

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'
  - 'Equal contribution'


date: '2023-08-01'
# Schedule page publish date (NOT publication's date).
publishDate: '2024-01-23T06:46:19.469371Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*Electronic Proceedings in Theoretical Computer Science*'
publication_short: In *QPL 2023*

doi: 10.4204/eptcs.384.1
links:
- name: URL
  url: http://dx.doi.org/10.4204/EPTCS.384.1

abstract: 'In this work, we present a generic approach to transform CSS codes by building upon their equivalence to phase-free ZX diagrams. Using the ZX calculus, we demonstrate diagrammatic transformations between encoding maps associated with different codes. As a motivating example, we give explicit transformations between the Steane code and the quantum Reed-Muller code, since by switching between these two codes, one can obtain a fault-tolerant universal gate set. To this end, we propose a bidirectional rewrite rule to find a (not necessarily transversal) physical implementation for any logical ZX diagram in any CSS code.

Then we focus on two code transformation techniques: _code morphing_, a procedure that transforms a code while retaining its fault-tolerant gates, and _gauge fixing_, where complimentary codes can be obtained from a common subsystem code (e.g., the Steane and the quantum Reed-Muller codes from the [[15,1,3,3]] code). We provide explicit graphical derivations for these techniques and show how ZX and graphical encoder maps relate several equivalent perspectives on these code-transforming operations.'

# Summary. An optional shortened abstract.
summary: 'We provide explicit graphical derivations for two code transformation techniques: _code morphing_ and _gauge fixing_, and show how several equivalent perspectives on these operations get related via ZX calculus and graphical encoder maps.'

tags: [ZX calculus, quantum error correction]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org


url_pdf: 'https://arxiv.org/abs/2307.02437'
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
url_poster: 'https://github.com/jackkyyh/ZXCSS/releases/tag/qip-2024'
# url_project: ''
url_slides: 'https://github.com/jackkyyh/ZXCSS/releases/tag/zx-meeting'
# url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
url_video: 'https://youtu.be/ZhfQxdjodNs'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Pushing Through the Encoder'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
<!-- 
{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
