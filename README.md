Hi, I’m Shraddha Piparia — Computational Biologist & ML Scientist 👋  

I build machine learning systems and scalable pipelines to understand disease biology from large-scale genomics, proteomics, and single-cell data. My work focuses on disease stratification, treatment-response heterogeneity, and reproducible analysis of high-dimensional biomedical data.

Ph.D. in Computer Science | Computational Biology (Genomics, ML, Multi-omics)

🌐 [Personal site](https://shraddhapiparia.github.io/)

---

## Tech Stack

**Machine Learning**
PyTorch · Representation Learning · VAEs · Transformers · SHAP · Clinical NLP

**Computational Biology**
GWAS · PRS · Single-cell RNA-seq · Multi-omics · UK Biobank · Olink  

**Engineering**
Nextflow · Docker · Spark · SLURM · GitHub Actions  

---

## Featured Projects

### [Genotype Representation Learning](https://github.com/shraddhapiparia/blockbased-genotype-embedding-analysis) (Ongoing)
Discovered latent asthma-related genomic structure without phenotype labels using an LD-aware VAE + transformer framework.
-   **Technical Highlight:** Identified HLA class II and PDE4D as independent genomic axes using block-level attribution (leave-one-block-out).
-   **Impact:** Recovered known asthma-related genomic structure and linked latent axes to HLA class II and PDE4D signals.

### [proteomics_npx_analysis](https://github.com/shraddhapiparia/proteomics_npx_analysis) (Ongoing)
Developed scalable pipelines for disease subtype discovery using Olink NPX proteomics.
-   **Technical Highlight:** Built Spark + SQL workflows to process population-scale data (~50K UK Biobank participants).
-   **Impact:** Defined neurocognitive vs. non-neurocognitive Long COVID subtypes using WHO-aligned symptom profiles.

### [sc-cell-state-benchmark](https://github.com/shraddhapiparia/sc-cell-state-benchmark)
A reproducible benchmarking framework for perturbation-aware cell-state scoring in single-cell RNA-seq.
-   **Technical Highlight:** End-to-end Scanpy pipeline comparing gene set scoring and rank-based approaches.
-   **Impact:** Recovered expected interferon-response biology in stimulated PBMC data and benchmarked scoring methods across cell types.

### [COVID-Radiology-Study](https://github.com/shraddhapiparia/COVID-Radiology-Study)
Interpretable ML to predict pediatric COVID-19 status from radiology text.
-   **Technical Highlight:** Extracted structured features from 2,500+ CXR impressions using radiology-specific NLP and SHAP values.
-   **Impact:** Surfaced clinically meaningful patterns from text alone with full model transparency.
-   **Publication:** Piparia S, Defante A, Tantisira K, Ryu J. *Using machine learning to improve our understanding of COVID-19 infection in children.* PLOS ONE 18(2): e0281666 (2023). [DOI](https://doi.org/10.1371/journal.pone.0281666)

### [ANOVA-like-GWAS-NextFlow](https://github.com/shraddhapiparia/ANOVA-like-GWAS-NextFlow)
A reproducible GWAS workflow to identify variants associated with clinically defined asthma endotypes. **Published in Respiratory Research (2025).**
-   **Technical Highlight:** Nextflow + R pipeline designed for HPC/SLURM execution with ANOVA-style modeling.
-   **Impact:** Enabled detection of subtype-specific genetic signals beyond traditional case-control designs.
-   **Publication:** Piparia S, Kho A, Desai B, Wong R, Sharma R, Celedon JC, Weiss ST, Mcgeachie M, Tantisira K. *A principal component analysis-based endophenotype definition for change in lung function and inhaled corticosteroid treatment response in childhood asthma.* Respiratory Research: 26:351 (2025). [DOI](https://link.springer.com/article/10.1186/s12931-025-03426-z)
-   **Publication:** Piparia S, Hadikhani P, Ziniti J, Hecker J, Kho A, Sharma R, Celedon JC, Weiss ST, Mcgeachie M, Tantisira K. *A Categorical ANCOVA Approach to Severity Endophenotype-Specific GWAS Childhood Asthma.* 2026. [DOI](https://www.mdpi.com/2075-4426/16/1/32)


### [miRNA_ics_interaction](https://github.com/shraddhapiparia/miRNA_ics_interaction)
Analysis of miRNA signatures associated with treatment response heterogeneity. 
-   **Technical Highlight:** Integrated multi-omic datasets to identify miR-584-5p as a key modulator of corticosteroid resistance.
-   **Impact:** Identified miR-584-5p as a candidate molecular marker linked to variability in corticosteroid response.
-   **Publication:** Piparia S, Kho A, Hadikhani P, Ban G-Y, Sharma R, Celedon JC, Weiss ST, Mcgeachie M, Tantisira K. *MicroRNA-584-5p As a Key Modulator of Inhaled Corticosteroid Resistance in Asthma.* AJRCCM, 2025. [DOI](https://academic.oup.com/ajrccm/article-abstract/211/Supplement_1/A5441/8336421)

## Additional Project
### [from-fastq-to-asthma-gwas](https://github.com/shraddhapiparia/from-fastq-to-asthma-gwas)
Production-style genomics template from raw sequencing data to interpretable genetic analysis.
- **Technical:** Modular workflow covering FASTQ QC, alignment, variant calling, GWAS, PRS, and eQTL interpretation.
- **Impact:** Provides a portable, reproducible blueprint for moving from raw sequencing files to genetic insight.

---

## Research and Writing
- [Research publications](https://scholar.google.com/citations?user=T3k1qhwAAAAJ&hl=en&oi=ao)
- [Technical articles and project write-ups](https://shraddhapiparia.github.io/articles.html)

---

## Focus & Values
I am dedicated to Scientific Reproducibility and Technical Scale. I enjoy building methods that move from raw data to interpretable biological insight through versioned environments, automated workflows, and reusable code.

