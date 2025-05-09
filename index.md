---
title: Welcome to the data repository
site:
  hide_outline: true
  hide_toc: true
  hide_title_block: false
---

# Introduction

|˶˙ᵕ˙ )ﾉﾞ
**Hello there!**

Welcome to the data repository. This site keeps record and archives the materials and devices characterisation from our research activity. The repository is grouped based on experimental method and batches. While the site groups the research data, an approved GitHub credential is and might be required for you to access the raw data and analysis process, as most of our research is not published with open research policy.

This webpage is created as part of the [Knowledge Book](https://docs.haposan.com/), in an effort to improve the management of research data. You might see some links to the Knowledge Book embedded in the analysis section of this repository.

---

# Quick jump - recent repositories
::::{grid} 1 1 2 3


:::{card} 
:link: perovskites/copper-mechanochemistry.md
:header: Materials
:footer: Open research policy: `N/A`
**Copper halide perovskites [Mechanochemistry]**
Date: 2023-present | Variant: 0D $A_3B_2X_5$ and 1D $AB_2X_3$
:::

:::{card} 
:link: perovskites/copper-mechanochemistry
:header: Devices
:footer: Open research policy: `N/A`
**MoS₂ [Mech. Exfoliation-EBL]**
Date: 2024-2025 | Variant: $MoS_2$ devices
:::

::::

---

# Navigation

## How to look around

You can quickly navigate through the sections using the **navigation bar** on the left side. There is also a **search box** (`ctrl+k` or `cmd+k`) on top of the page to help you find any content in this web swiftly.



## How to retrieve data - and update changes

The fastest way to retrieve data is to download the GitHub repository as a ZIP. However, changes, analyses, and other files you add on your computer cannot be tracked by other users. While it might be easy to use cloud-based file management such as Google Drive or OneDrive, these platform lack the feature to **track and supervise changes** to the repository.

What you can do instead, is to clone the repository with Git on your machine. I highly recommend [GitHub Desktop](https://desktop.github.com/download/) to easily clone the repository and track changes. After you are done, or at least completed a major step, you can "re-upload" the files to the repository with "Commit" and "Push" buttons on [GitHub Desktop](https://desktop.github.com/download/). Afterwards, the Repository Manager will assess your change and integrate it into the central repository. The new version, old versions, and all the changes are tracked and safely stored. These features offer the advantage of having **redundancies** in our system.

```{hint}
:class: dropdown
**Why do we use Git/ GitHub?**

GitHub is a powerful platform for managing not only software code but also research data in materials science. It enables version control for datasets, simulation inputs, and analysis scripts, ensuring full traceability and reproducibility of scientific workflows. Researchers can collaborate effectively through GitHub’s tools for tracking changes, submitting pull requests, and documenting methods. By storing structured, text-based research artifacts—like Jupyter notebooks, VASP inputs, or ML configs—GitHub supports the FAIR principles and enhances data integrity through secure, auditable logs. It integrates with platforms like Zenodo for DOI archiving, Binder for launching notebooks, and GitHub Actions for automating tasks. While it’s best suited for smaller, text-based files, large data can be managed via Git LFS or linked external repositories. Overall, GitHub strengthens research transparency, collaboration, and long-term accessibility in materials science.
```

---
# User access
By default, if you are a co-author, collaborator, or one of the technician/ research engineer working on the project, you will already have access or prompted to obtain one at the beginning of the project. If you require clearance, please contact me by sending an email to repo@haposan.com or text me via any available channels.


```{attention}

**Attention: GitHub account is required**

The research data is stored and maintained with the use of Git, specifically in a platform called GitHub. If you don't have an account already, you can register for GitHub by clikcing the button below. **Use your education institution email for free GitHub pro packages!**

{button}`Register for GitHub<https://github.com/signup?source=form-home-signup&user_email=>`
```



---
# Acknowledgement
This repository is inspired and built with the principles of [Research Repositories 101 of Nielsen Norman Group](https://www.nngroup.com/articles/research-repositories/). This web is powered by [MyST](https://mystmd.org/made-with-myst), [Jupyter Book](https://jupyterbook.org/en/stable/intro.html), and [Vercel](https://vercel.com/).