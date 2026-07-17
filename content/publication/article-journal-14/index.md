---
title: 'CryoLigATE: Enhancing the resolvability of cryo-EM maps in protein-ligand complexes using deep learning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Rebecca J. Howard
- Erik Lindahl

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2026-07-10T00:00:00Z'
doi: 'https://github.com/nandanhaloi123/CryoLigATE'

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
# publication: In *Hugo Blox Builder Conference*
publication_short: In *Preparation*

abstract: Cryo-electron microscopy (cryo-EM) has become a central tool for structure-based drug discovery, yet ligand-binding sites often remain substantially less well resolved than the surrounding protein, limiting reliable atomic interpretation. Existing deep learning approaches have markedly improved global cryo-EM map quality but are trained predominantly on protein architectures and frequently fail to recover ligand densities. Here we present CryoLigATE, a deep learning framework specifically designed to enhance densities associated with protein-bound ligands in cryo-EM maps. We curated a chemically and structurally diverse dataset of more than 6,000 protein-ligand complexes from the EMDB and PDB, encompassing drug-like molecules, lipids, steroids, carbohydrates and other ligand classes, and trained a hybrid convolutional-transformer network to enhance local density around binding pockets. During inference, CryoLigATE automatically extracts the target region from a preliminary atomic model, requiring no manual map preparation and completing localized refinement in seconds on a desktop GPU. Evaluation on an independent test set of 649 complexes demonstrates substantial improvements in ligand resolvability, particularly for maps with poorly resolved binding sites, while preserving high-quality experimental densities. The enhanced maps recover chemically meaningful features, including ligand functional groups and topological continuity, enabling more confident atomic modeling. By explicitly learning the structural diversity of ligand features, CryoLigATE addresses a longstanding limitation of cryo-EM map enhancement and provides a useful framework for improving structural interpretation and structure-guided drug discovery.


# Summary. An optional shortened abstract.
summary: " "

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# url_pdf: ''
# url_code: 'http://arxiv.org/pdf/1512.04133v1'
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

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
# projects:
#   - example

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
