# Micro- and Nanoplastics: Crossing the Blood-Brain Barrier to Drive Sustained Neuroinflammation and HPA Axis Dysregulation

This repository contains the manuscript, reference database, and automated publishing pipeline for an academic review examining how environmental micro- and nanoplastics (MNPs) penetrate the Central Nervous System (CNS) and disrupt endocrine homeostasis.

The project was authored for the Immunology (BT335IU) course at the School of Biotechnology, International University – Vietnam National University, Ho Chi Minh City.

---

## Direct Access for Readers

You do not need to install Git, R, Python, or Quarto to read or review this manuscript. Pre-compiled documents, the interactive web preview, and the complete replication bundle are available directly below.

| Format | Access Link | Description |
|:---|:---|:---|
| **Web Article (In-Browser)** | [Read Online via GitHub Pages](https://ht2905.github.io/microplastic-neurotoxicity-paper/) | Formatted interactive article with floating table of contents and high-resolution figures. Accessible on any browser or mobile device. |
| **Microsoft Word (.docx)** | [Direct Download Latest DOCX](https://github.com/ht2905/microplastic-neurotoxicity-paper/releases/latest/download/microplastic-neurotoxicity_manuscript.docx) | Fully styled Word document with Vancouver numbered citations and embedded figures. Ideal for track changes, reviewing, and grading. |
| **Standalone HTML (.html)** | [Direct Download Standalone HTML](https://github.com/ht2905/microplastic-neurotoxicity-paper/releases/latest/download/microplastic-neurotoxicity_manuscript.html) | Single self-contained HTML file with all figures and styles embedded. Can be saved locally and opened offline without Word. |
| **Complete Replication Package (.zip)** | [Download Replication Package (.zip)](https://github.com/ht2905/microplastic-neurotoxicity-paper/releases/latest/download/microplastic-neurotoxicity_replication-package.zip) | Complete self-contained research compendium containing the compiled Word manuscript, offline HTML, raw Quarto Markdown source, BibTeX bibliography, figures, and CSL styles. |
| **Verification Checksums** | [Download SHA-256 Checksums](https://github.com/ht2905/microplastic-neurotoxicity-paper/releases/latest/download/checksums.sha256) | Cryptographic SHA-256 hashes to verify release package and file integrity. |
| **Plain-Text Source (.qmd)** | [Read Source on GitHub](microplastic-neurotoxicity_manuscript.qmd) | Raw Quarto Markdown source file containing text, academic metadata, and citation keys. |

---

## Manuscript Overview

### Academic Metadata

| Property | Details |
|:---|:---|
| Title | Micro- and Nanoplastics: Crossing the Blood-Brain Barrier to Drive Sustained Neuroinflammation and HPA Axis Dysregulation |
| Author | Tran Quoc Hoang (Student ID: BTBTWE24036) |
| Institution | School of Biotechnology, International University – Vietnam National University, Ho Chi Minh City |
| Course | Immunology (BT335IU) |
| Academic Advisor | Assoc. Prof. Hoai T. T. Nguyen |
| Date | December 2025 |
| Keywords | Microplastics, Nanoplastics, Blood-Brain Barrier, Neuroinflammation, Microglia, NLRP3 Inflammasome, Gut-Brain Axis, HPA Axis |

### Abstract Summary

Micro- and nanoplastics (MNPs) represent pervasive environmental contaminants that enter mammalian organisms via inhalation and ingestion. Due to their diminutive nanoscale dimensions, nanoplastics can traverse biological barriers—most critically the Blood-Brain Barrier (BBB)—through endocytic pathways and the "Trojan Horse" transport mechanism mediated by circulating immune cells.

Once inside the brain parenchyma, non-degradable particles induce persistent microglial activation via frustrated phagocytosis. This failure to digest foreign synthetic debris triggers the NLRP3 inflammasome cascade, driving chronic cleavage of caspase-1 and sustained secretion of potent pro-inflammatory cytokines (IL-1beta, IL-18, TNF-alpha). 

Concurrently, peripheral gut exposure damages mucosal tight junctions, permitting systemic leakage of bacterial endotoxins and inflammatory mediators via the Gut-Brain Axis (GBA). Together, central and peripheral immune insults induce neurotoxicity, chronic Hypothalamic-Pituitary-Adrenal (HPA) axis dysregulation, glucocorticoid receptor resistance, heightened baseline anxiety-like behaviors, and cognitive deficits.

### Mechanistic Summary

```mermaid
flowchart TD
    Exposure["Environmental MNP Exposure\n(Ingestion and Inhalation)"] --> Uptake["Systemic Translocation &\nGut Mucosal Barrier Breakdown"]
    Uptake --> GBA["Gut-Brain Axis Signaling\n(Endotoxin Leakage & Cytokine Storm)"]
    Uptake --> BBB["Translocation Across the BBB\n(Endocytosis & Trojan Horse Effect)"]
    BBB --> Microglia["Microglial Uptake &\nFrustrated Phagocytosis"]
    Microglia --> NLRP3["NLRP3 Inflammasome\nCascade Assembly"]
    NLRP3 --> Cytokines["Sustained Pro-inflammatory Cytokines\n(IL-1beta, IL-18, TNF-alpha)"]
    GBA --> Cytokines
    Cytokines --> Pathology["Chronic HPA Axis Dysregulation,\nGlucocorticoid Resistance, &\nNeurobehavioral Deficits"]
```

---

## Figure Guide and Biological Context

The manuscript incorporates four core diagrams illustrating distinct stages of MNP-induced pathology. All visual assets are stored in the [`figures/`](figures/) directory:

| Figure | Filename | Biological Focus |
|:---|:---|:---|
| **Fig. 1** | [`figures/mnp_entry-routes.jpeg`](figures/mnp_entry-routes.jpeg) | Primary exposure pathways (inhalation and ingestion), SPI polymer classifications, and physical transport across vascular endothelium into the CNS. |
| **Fig. 2** | [`figures/microglia_activation-states.jpg`](figures/microglia_activation-states.jpg) | Morphological and functional transitions of quiescent microglia into Disease-Associated Microglia (DAMs) and Injury-Responsive Microglia (IRMs). |
| **Fig. 3** | [`figures/gut-brain-axis_inflammatory-pathways.jpg`](figures/gut-brain-axis_inflammatory-pathways.jpg) | Intestinal invasion, epithelial barrier breakdown, systemic oxidative stress pathways, and peripheral-to-central cytokine transmission. |
| **Fig. 4** | [`figures/hpa-axis_acute-chronic-dysregulation.png`](figures/hpa-axis_acute-chronic-dysregulation.png) | Comparison of protective acute cortisol feedback loops versus chronic glucocorticoid receptor resistance and HPA axis exhaustion. |

---

## Biomedical Abbreviations Reference

| Abbreviation | Full Scientific Term | Physiological Context |
|:---|:---|:---|
| **BBB** | Blood-Brain Barrier | Selective endothelial barrier protecting the brain microenvironment. |
| **CNS** | Central Nervous System | Brain and spinal cord neural networks. |
| **DAMs** | Disease-Associated Microglia | Specialized neurodegenerative microglial activation phenotype. |
| **GBA** | Gut-Brain Axis | Bidirectional biochemical signaling between the GI tract and CNS. |
| **HPA** | Hypothalamic-Pituitary-Adrenal Axis | Primary neuroendocrine stress and immune regulation system. |
| **IL-1beta** | Interleukin-1 beta | Key pro-inflammatory cytokine matured by the NLRP3 inflammasome. |
| **IL-6** | Interleukin-6 | Pleiotropic cytokine mediating systemic inflammatory responses. |
| **IL-18** | Interleukin-18 | Inflammasome-activated cytokine stimulating interferon-gamma. |
| **IRMs** | Injury-Responsive Microglia | Phenotype specialized for acute focal CNS tissue damage. |
| **MNPs** | Micro- and Nanoplastics | Synthetic polymer particles ranging from sub-micron to 5 mm. |
| **NLRP3** | NOD-like Receptor Protein 3 | Intracellular sensor forming the inflammasome complex upon lysosomal rupture. |
| **TNF-alpha** | Tumor Necrosis Factor alpha | Master pro-inflammatory cytokine driving vascular permeability and apoptosis. |

---

## Local Compilation (Optional)

If you wish to modify the manuscript text, edit citations, or compile locally:

### Requirements
* [Quarto CLI](https://quarto.org/docs/get-started/) (version 1.3 or higher).
* A word processor (Microsoft Word or LibreOffice) or a web browser.
* *Note: No R, Python, or LaTeX installation is required.*

### Build Commands

```bash
# 1. Clone repository
git clone https://github.com/ht2905/microplastic-neurotoxicity-paper.git
cd microplastic-neurotoxicity-paper

# 2. Render both Word and HTML outputs
quarto render

# 3. Or render specifically to Word (.docx)
quarto render microplastic-neurotoxicity_manuscript.qmd --to hikmah-manuscript-docx

# 4. Or render specifically to standalone HTML (.html)
quarto render microplastic-neurotoxicity_manuscript.qmd --to html --output index.html
```

---

## Citation and Academic Attribution

If you reference this work or adapt its reproducible structure, please cite:

```bibtex
@misc{tran2025microplastics,
    author       = {Tran, Quoc Hoang},
    title        = {Micro- and Nanoplastics: Crossing the Blood-Brain Barrier to Drive Sustained Neuroinflammation and HPA Axis Dysregulation},
    year         = {2025},
    howpublished = {School of Biotechnology, International University - VNU-HCM},
    note         = {Immunology Coursework (BT335IU)}
}
```

* **Author:** Tran Quoc Hoang
* **Affiliation:** School of Biotechnology, International University – Vietnam National University, Ho Chi Minh City
* **Email:** tranquochoang@protonmail.com
* **Repository:** [https://github.com/ht2905/microplastic-neurotoxicity-paper](https://github.com/ht2905/microplastic-neurotoxicity-paper)
