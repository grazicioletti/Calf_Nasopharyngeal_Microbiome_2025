# Calf_Nasopharyngeal_Microbiome_2025

**Author:** Grazielle Cioletti  
**Affiliation:** The Pennsylvania State University  

This repository contains processed data and analysis scripts for the study:  
*“Low-Level β-Lactams in Milk Replacer Delay Nasopharyngeal Microbiome Maturation in Dairy Calves.”*

---

## 📂 Folder Overview

### `data/`
- `AMC-metadata.csv`: Sample metadata (Age, Diet, Treatment, Project_ID)
- `ps_tax.RDS`: Phyloseq object for taxonomic analysis
- `rawps_amr.rds`: Phyloseq object for AMR analysis

### `scripts/`
Contains all reproducible R Markdown files:
- `AMC-Tax_Stats.Rmd`: Taxonomic alpha/beta diversity, composition, and statistics  
- `AMC-AMR_Stats.Rmd`: AMR++ diversity, resistance class abundance, and heatmaps

### `taxonomic/`
Exported CSV tables from taxonomic analysis:
- Alpha/beta diversity summaries
- Mann–Whitney and Kruskal–Wallis results
- PERMANOVA and pairwise ADONIS outputs
- Relative abundance tables

### `amr/`
Exported CSV tables from AMR++ analysis:
- Alpha and beta diversity summaries
- Pairwise ADONIS results
- AMR class and heatmap data
- Metadata used for plotting

---

## ⚙️ Reproducibility
All analyses were performed in **R 4.3+** using:
`phyloseq`, `microViz`, `microbiome`, `decontam`, `ggpubr`, `ComplexHeatmap`, and `pairwiseAdonis`.

Each R Markdown file is self-contained and reproducible.

---

## 📬 Contact
**Grazielle Cioletti**  
Email: [gkc5305@psu.edu](mailto:gkc5305@psu.edu)
