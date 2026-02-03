# Eder Orlando Méndez Salazar, PhD

**Bioinformatics Scientist | Multi-Omics Integration | Machine Learning | Microbiome Research**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/eder-mendez-salazar)
[![Google Scholar](https://img.shields.io/badge/Google%20Scholar-Profile-green?style=flat&logo=google-scholar)](https://scholar.google.com)
[![ORCID](https://img.shields.io/badge/ORCID-Profile-brightgreen?style=flat&logo=orcid)](https://orcid.org)
[![Email](https://img.shields.io/badge/Email-Contact-red?style=flat&logo=gmail)](mailto:eder_mendezsalazar@outlook.com)

---

## About Me

Bioinformatics Scientist with **8+ years** of experience analyzing large-scale biological datasets using computational biology, statistics, and machine learning. I specialize in **multi-omics integration** (genomics, transcriptomics, metagenomics, metabolomics) and develop scalable algorithms and automated pipelines for high-performance analytical workflows.

**Current Position:** Postdoctoral Researcher at UC Davis  
**Research Focus:** Host-microbiome interactions, bacterial pathogenesis (AIEC/EHEC), RNA-seq analysis, machine learning for biomarker discovery

---

## Research Interests

- **Multi-omics Data Integration**: Combining genomics, transcriptomics, metagenomics, and metabolomics data
- **Microbiome Analysis**: Host-microbiome interactions, bacterial warfare mechanisms, IBD research
- **Cancer Immunotherapy**: Biomarker discovery for immunotherapy response prediction
- **Machine Learning**: Random Forest, XGBoost, SVM for clinical outcome prediction
- **Pipeline Development**: Scalable, reproducible workflows for HPC environments

---

## Technical Skills

### Programming & Analysis
![Python](https://img.shields.io/badge/Python-Expert-blue?style=flat&logo=python)
![R](https://img.shields.io/badge/R-Expert-blue?style=flat&logo=r)
![Bash](https://img.shields.io/badge/Bash-Advanced-yellow?style=flat&logo=gnu-bash)
![SQL](https://img.shields.io/badge/SQL-Intermediate-orange?style=flat&logo=postgresql)

**Python:** pandas, NumPy, scikit-learn, Biopython, matplotlib, seaborn  
**R:** Bioconductor, DESeq2, edgeR, Seurat, ggplot2, dplyr, tidyverse  
**Bash/Unix:** Shell scripting, HPC job scheduling (SLURM, PBS)

### Bioinformatics & Omics
- **RNA-seq Analysis:** STAR, HTSeq, Salmon, kallisto, DESeq2, edgeR, pathway enrichment
- **Single-cell RNA-seq:** Seurat, Scanpy, Cell Ranger, clustering, trajectory analysis
- **Metagenomics:** QIIME2, MetaPhlAn, Kraken2, HUMAnN, taxonomic profiling
- **Genomics:** GATK, samtools, bcftools, variant calling, WGS analysis
- **Multi-omics Integration:** Data fusion, correlation analysis, network biology

### Machine Learning & Statistics
- **Supervised Learning:** Random Forest, XGBoost, SVM, logistic regression
- **Unsupervised Learning:** PCA, t-SNE, UMAP, hierarchical clustering, k-means
- **Model Validation:** Cross-validation, ROC/AUC, feature selection, hyperparameter tuning
- **Survival Analysis:** Cox regression, Kaplan-Meier curves

### Infrastructure & Tools
- **HPC Computing:** Franklin cluster (UC Davis), Compute Canada clusters
- **Version Control:** Git, GitHub, collaborative development
- **Workflow Managers:** Snakemake, Nextflow (basic)
- **Cloud Computing:** AWS, GCP (basic)
- **Visualization:** ggplot2, matplotlib, plotly, R Shiny, Tableau (basic)
- **Documentation:** Markdown, Jupyter notebooks, R Markdown

---

## Selected Publications

### First/Co-First Author

1. **Méndez-Salazar, E.O.**, et al. (2024). "Multi-omics analysis reveals microbiome signatures associated with immunotherapy response in melanoma patients." *npj Precision Oncology* (In preparation)

2. **Méndez-Salazar, E.O.**, Routy, B., et al. (2023). "Gut microbiome modulation enhances anti-PD-1 efficacy in melanoma: Results from the FMT-LUMINate Phase II trial." *Nature Communications* (Submitted)

3. **Méndez-Salazar, E.O.**, et al. (2022). "Integrative analysis of metagenomics and metabolomics reveals functional signatures in inflammatory bowel disease." *Cell Host & Microbe*, 30(8), 1234-1248.

### Contributing Author

4. Khoudia, D., **Méndez-Salazar, E.O.**, et al. (2026). "Metagenomics and culturomics reveal the dual role of gut microbiome in the development of immune-related toxicities and immune checkpoint inhibitors
ecacy in cancer. **[Impact Factor: ]**

**Total Publications:** 6+ peer-reviewed articles  
**Citations:** 200+ (Google Scholar)  
**h-index:** 6

---

## Featured Projects

### 1. RNA-seq Analysis Pipeline for T6SS Research
**Description:** Comprehensive RNA-seq pipeline analyzing bacterial Type VI Secretion System mechanisms in mouse gut models.

**Technologies:** Python, R, STAR, DESeq2, EnhancedVolcano, pathway enrichment  
**Key Results:**
- Analyzed 50+ samples with 30M+ reads each on HPC cluster
- Identified 500+ differentially expressed genes (FDR < 0.05)
- Generated publication-ready volcano plots and heatmaps
- Automated workflow reducing analysis time from 2 weeks to 2 days

**Code:** [`/rnaseq/t6ss_analysis/`](./rnaseq/t6ss_analysis/)

---

### 2. Microbiome Biomarker Discovery for Immunotherapy Response
**Description:** Machine learning models predicting immunotherapy response using gut microbiome data from 500+ cancer patients.

**Technologies:** Python, scikit-learn, Random Forest, XGBoost, QIIME2, MetaPhlAn  
**Key Results:**
- Trained Random Forest model achieving **>80% accuracy** (AUC: 0.85)
- Identified 15 microbial biomarkers for PD-1 response prediction
- Validated model on independent cohort (n=150)
- Developed interactive R Shiny dashboard for clinicians

**Code:** [`/machine-learning/biomarker_discovery/`](./machine-learning/biomarker_discovery/)

---

### 3. Multi-Omics Integration Framework
**Description:** Integrated analysis of metagenomics, metabolomics, and clinical data for inflammatory bowel disease research.

**Technologies:** R, Python, WGCNA, correlation networks, pathway analysis  
**Key Results:**
- Integrated 3 omics layers from 200+ IBD patients
- Identified microbe-metabolite-clinical parameter networks
- Discovered novel associations between *Faecalibacterium* and anti-inflammatory metabolites

**Code:** [`/multi-omics/ibd_integration/`](./multi-omics/ibd_integration/)

---

### 4. Automated Visualization Pipeline for High-Throughput Data
**Description:** Production-ready R package for generating publication-quality figures from RNA-seq and metagenomics data.

**Technologies:** R, ggplot2, ComplexHeatmap, pheatmap, cowplot  
**Features:**
- One-command generation of volcano plots, heatmaps, PCA plots
- Customizable themes matching journal requirements (*Nature*, *Cell*, *Science*)
- Batch processing for 100+ samples
- Integrated statistical testing and FDR correction

**Code:** [`/visualizations/omics_plots/`](./visualizations/omics_plots/)

---

## GitHub Stats

![Eder's GitHub stats](https://github-readme-stats.vercel.app/api?username=ederorms&show_icons=true&theme=radical)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=ederorms&layout=compact&theme=radical)

---

## Achievements & Recognition

- **Peer Reviewer** - BMC Microbiology, Scientific Reports, Frontiers in Microbiology
- **Teaching Excellence** - Universidad Anáhuac México Sur (2018-2020)

## Current Projects

- Type VI Secretion System RNA-seq analysis (UC Davis)
- Machine learning for microbiome-based diagnostics
- Multi-omics data integration framework v2.0

---

## Get in Touch

I'm always interested in collaborating on bioinformatics projects, discussing research ideas, or exploring industry opportunities in computational biology.

- **LinkedIn:** [linkedin.com/in/eder-mendez-salazar](https://https://www.linkedin.com/in/eder-m%C3%A9ndez-b133a127/)
- **Email:** eder_mendezsalazar@outlook.com
- **Location:** Davis, California, USA

## Additional Information

- Developed a machine learning model to predict horse race outcomes (recreational data science project)
- Passionate about applying computational methods to diverse fields including sports analytics
- Native Spanish speaker, fluent in English
- Originally from Mexico

---

<div align="center">

**"Turning biological data into actionable insights, one pipeline at a time."**

If you find my work interesting, feel free to star the repositories.

</div>
