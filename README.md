# Hi there, I’m Shraddha Piparia — Computational Biologist & ML Scientist 👋

Computational biologist and machine learning scientist working at the intersection of genomics, proteomics, single-cell biology, and reproducible computational pipelines.

I have a Ph.D. in Computer Science and currently work in computational biology, building ML methods and scalable workflows for disease heterogeneity, patient stratification, and treatment response.

* Genomics + representation learning
* Single-cell and multi-omics analysis
* UK Biobank and large-scale proteomics
* Reproducible bioinformatics pipelines

🌐 [Personal site](https://shraddhapiparia.github.io/)

---

## Start Here

If you only look at a few projects, these are the best entry points:

1. **Genotype representation learning** – LD-aware VAE + transformer framework for discovering latent genomic structure and asthma-related biology.
2. **Single-cell benchmarking** – reproducible single-cell workflows and perturbation-aware cell-state scoring.
3. **Large-scale proteomics** – Olink NPX and UK Biobank pipelines for Long COVID and disease subtype discovery.
4. **End-to-end reproducible genomics pipelines** – Nextflow, Docker, and configuration-driven workflows from raw sequencing data to analysis.

---

## Featured Projects

### [blockbased-genotype-embedding-analysis](https://github.com/shraddhapiparia/blockbased-genotype-embedding-analysis)

LD-aware representation learning for genotype data using VAEs and transformers.

* Recovering asthma-related genomic structure without phenotype labels
* Identified strong HLA class II and PDE4D signals from latent embeddings
* Demonstrated improved latent organization versus baseline approaches

**Key result:** recovered known asthma biology with embedding structure achieving ARI = 0.999 and revealing multiple independent HLA haplotype axes.

### [sc-cell-state-benchmark](https://github.com/shraddhapiparia/sc-cell-state-benchmark)

Benchmarking perturbation-aware cell-state scoring methods in single-cell RNA-seq data.

* Reproducible Scanpy workflow from preprocessing through scoring and visualization
* Compared multiple scoring approaches and control gene sets
* Includes interferon-stimulated PBMC analysis and communication scoring

**Key result:** built an interpretable benchmark where interferon-response programs achieved near-perfect separation while preserving biologically meaningful cell-state differences.

### [proteomics_npx_analysis](https://github.com/shraddhapiparia/proteomics_npx_analysis)

Scalable Olink NPX proteomics analysis for pediatric Long COVID and UK Biobank replication.

* Disease subgroup discovery using WHO-defined symptom profiles
* Spark + SQL workflows for tens of thousands of participants
* Regression, enrichment, volcano plots, and replication analyses

**Key result:** developed reproducible pipelines to compare neurocognitive and non-neurocognitive Long COVID subtypes across pediatric and UK Biobank cohorts.

### [from-fastq-to-asthma-gwas](https://github.com/shraddhapiparia/from-fastq-to-asthma-gwas)

Educational but production-style genomics workflow from FASTQ through variant calling, GWAS, and biological interpretation.

* Covers QC, alignment, variant calling, annotation, GWAS, PRS, and eQTL analysis
* Includes Nextflow, Docker, and reproducible configuration files
* Designed to demonstrate complete end-to-end genomics workflow design

**Key result:** provides a reproducible template for moving from raw sequencing data to interpretable disease-associated variants.

### [miRNA_ics_interaction](https://github.com/shraddhapiparia/miRNA_ics_interaction)

Analysis of miRNA signatures associated with inhaled corticosteroid response in asthma.

* Differential expression, enrichment, and subgroup analyses
* Focus on miR-584-5p and neurocognitive phenotype differences
* Includes publication-ready plots and reproducible analysis scripts

**Key result:** identified candidate miRNA signatures associated with treatment response heterogeneity.

---

## Selected Technical Themes

### Machine Learning & Modeling
Python · PyTorch · Representation learning · VAEs · Transformers · SHAP · NLP 

### Computational Biology
Genomics · GWAS/PLINK · Polygenic Risk Scores · Single-cell RNA-seq · Multi-omics · UK Biobank · Scanpy · Seurat · Olink NPX proteomics · NGS pipelines · WNN integration

### Scalable & Reproducible Infrastructure
Nextflow · Docker · Conda · SLURM · GitHub Actions · Spark SQL · UK Biobank RAP

### Data & Visualization
NumPy · Pandas · scikit-learn · Matplotlib · Seaborn · SQL · PySpark

---


## Publications and Writing

* Research publications: [https://scholar.google.com/citations?user=T3k1qhwAAAAJ&hl=en&oi=ao]
* Personal website: [https://shraddhapiparia.github.io/]

---

## What I Care About

I enjoy building computational biology projects that are both scientifically meaningful and technically reproducible: methods that can move from raw data to interpretable biological insight, with clear workflows, versioned environments, and reusable code.

