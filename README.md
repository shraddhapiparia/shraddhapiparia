Hi, I’m Shraddha Piparia — Computational Biologist & ML Scientist 👋  

I build machine learning systems and scalable pipelines to understand disease biology from large-scale genomics, proteomics, and single-cell data.

- Designed representation learning frameworks uncovering latent genomic structure (ARI = 0.999)
- Built Spark-based pipelines scaling to ~50K UK Biobank participants
- Developed end-to-end reproducible workflows from raw sequencing data to biological insight

Ph.D. in Computer Science | Computational Biology (Genomics, ML, Multi-omics)

🌐 [Personal site](https://shraddhapiparia.github.io/)

---

## What I Do

I focus on building systems that turn complex biological data into actionable insights:

- Representation learning for genomics (VAEs, transformers, embeddings)
- Multi-omics integration (single-cell RNA-seq + ATAC-seq)
- Disease stratification and subtype discovery
- Scalable pipelines for large cohort data (UK Biobank, Olink)
- Reproducible ML workflows (Nextflow, Docker, Spark)

---

## Start Here

If you're evaluating my work, these projects best represent my strengths:

- **Genotype Representation Learning**  
  ML + genomics → discovering latent disease structure without labels  

- **Single-Cell Benchmarking**  
  Reproducible pipelines + interpretable biological scoring  

- **Large-Scale Proteomics (UK Biobank)**  
  Population-scale analysis + disease subtype discovery  

- **End-to-End Genomics Pipeline**  
  Production-style workflow from FASTQ → GWAS → interpretation

---

## Featured Projects

### Genotype Representation Learning [Ongoing](https://github.com/shraddhapiparia/blockbased-genotype-embedding-analysis)

Discovered latent asthma-related genomic structure without phenotype labels using deep representation learning.

- Designed an LD-aware VAE + transformer framework to learn hierarchical genotype embeddings
- Identified HLA class II and PDE4D as independent genomic axes
- Implemented block-level attribution using perturbation (leave-one-block-out) to quantify each region’s contribution to learned embeddings
- Extended to within-block SNP attribution to localize signal inside LD blocks 

**Impact:** Recovered known asthma biology with ARI = 0.999 and introduced an interpretable framework linking latent genomic representations to specific regions and variants.  


### [sc-cell-state-benchmark](https://github.com/shraddhapiparia/sc-cell-state-benchmark)

Built a reproducible benchmarking framework for perturbation-aware cell-state scoring in single-cell RNA-seq.

- Developed end-to-end Scanpy pipeline (preprocessing → clustering → scoring)  
- Compared gene set scoring, mean expression, and rank-based approaches with matched controls  
- Applied to interferon-stimulated PBMC data with cell-type-specific program evaluation  

**Impact:** Demonstrated near-perfect separation of interferon-response programs while preserving biologically meaningful cell-state structure.


### proteomics_npx_analysis [Ongoing](https://github.com/shraddhapiparia/proteomics_npx_analysis)

Developed scalable pipelines for disease subtype discovery using Olink NPX proteomics across pediatric and UK Biobank cohorts.

- Built Spark + SQL workflows to process tens of thousands of participants  
- Defined Long COVID subgroups using WHO-aligned symptom profiles  
- Performed regression, enrichment, and cross-cohort replication analyses  

**Impact:** Enabled reproducible comparison of neurocognitive vs non-neurocognitive Long COVID subtypes at population scale.  

### [COVID-Radiology-Study](https://github.com/shraddhapiparia/COVID-Radiology-Study)

Built an interpretable ML pipeline to predict pediatric COVID-19 status from chest X-ray radiology impressions, combining clinical NLP with SHAP-based explanation. **Published in PLOS ONE (2023).**

- Extracted structured features from 2,572 CXR impressions across 721 pediatric patients using radiology-specific text processing and negation handling
- Trained incremental Random Forest models with progressively richer clinical context (demographics → symptoms → impressions)
- Used SHAP values to identify radiographic patterns and clinical features most predictive of pediatric COVID-19

**Impact:** Demonstrated that interpretable ML on radiology impression text — without raw imaging — can surface clinically meaningful patterns of pediatric COVID-19, with full transparency for clinical review.

**Publication:** Piparia S, Defante A, Tantisira K, Ryu J. *Using machine learning to improve our understanding of COVID-19 infection in children.* PLOS ONE 18(2): e0281666 (2023). [DOI](https://doi.org/10.1371/journal.pone.0281666)

### **Genomics / GWAS**

### [from-fastq-to-asthma-gwas](https://github.com/shraddhapiparia/from-fastq-to-asthma-gwas)

Designed an end-to-end, production-style genomics pipeline from raw sequencing data to disease-associated variants.

- Implemented modular workflow covering QC → alignment → variant calling → GWAS → PRS → eQTL  
- Structured with Nextflow-style design principles and reproducible environments (Conda)  
- Ensured portability by excluding large artifacts while preserving full reproducibility  

**Impact:** Provides a scalable, reproducible template for translating raw sequencing data into interpretable genetic insights.

### [ANOVA-like-GWAS-NextFlow](<repo-link>)

Built a reproducible GWAS workflow to identify genetic variants associated with clinically defined asthma subtypes (endotypes).

- Implemented Nextflow + R pipeline for batch-wise genome-wide SNP testing  
- Applied ANOVA-style models to capture genetic differences across multiple disease subtypes  
- Designed for HPC/SLURM execution with reproducible inputs and smoke-test examples  

**Impact:** Demonstrates how incorporating clinically defined endotypes into GWAS enables detection of subtype-specific genetic signals beyond traditional case–control designs.

**Publication:** Piparia S, Kho A, Desai B, Wong R, Sharma R, Celedon JC, Weiss ST, Mcgeachie M, Tantisira K. *A principal component analysis-based endophenotype definition for change in lung function and inhaled corticosteroid treatment response in childhood asthma.* Respiratory Research: 26:351 (2025). [DOI](https://link.springer.com/article/10.1186/s12931-025-03426-z)

**Publication:** Piparia S, Hadikhani P, Ziniti J, Hecker J, Kho A, Sharma R, Celedon JC, Weiss ST, Mcgeachie M, Tantisira K. *A Categorical ANCOVA Approach to Severity Endophenotype-Specific GWAS Childhood Asthma.* 2026. [DOI](https://www.mdpi.com/2075-4426/16/1/32)

### [miRNA_ics_interaction](https://github.com/shraddhapiparia/miRNA_ics_interaction)

Analyzed miRNA signatures associated with treatment response heterogeneity in asthma.

- Performed differential expression and enrichment analysis across patient subgroups  
- Focused on miR-584-5p and neurocognitive phenotype interactions  
- Generated publication-ready visualizations and reproducible workflows  

**Impact:** Identified candidate miRNA markers linked to variability in inhaled corticosteroid response.

**Publication:** Piparia S, Kho A, Hadikhani P, Ban G-Y, Sharma R, Celedon JC, Weiss ST, Mcgeachie M, Tantisira K. *MicroRNA-584-5p As a Key Modulator of Inhaled Corticosteroid Resistance in Asthma.* AJRCCM, 2025. [DOI](https://academic.oup.com/ajrccm/article-abstract/211/Supplement_1/A5441/8336421)

---

## Engineering & Scale

- Processed genomic datasets with millions of variants
- Built Spark pipelines for tens of thousands of participants (UK Biobank)
- Designed reproducible workflows using Nextflow, Docker, and Conda
- Structured projects for portability, CI validation, and reusability

---

## Tech Stack

**Machine Learning**
PyTorch · Representation Learning · VAEs · Transformers · SHAP · Clinical NLP

**Computational Biology**
GWAS · PRS · Single-cell RNA-seq · Multi-omics · UK Biobank · Olink  

**Infrastructure**
Nextflow · Docker · Spark · SLURM · GitHub Actions  

**Data**
Python · Pandas · NumPy · SQL · PySpark

---


## Research and Writing

* [Research publications](https://scholar.google.com/citations?user=T3k1qhwAAAAJ&hl=en&oi=ao)
* [Technical articles and project write-ups](https://shraddhapiparia.github.io/articles.html)

---

## What I Care About

I enjoy building computational biology projects that are both scientifically meaningful and technically reproducible: methods that can move from raw data to interpretable biological insight, with clear workflows, versioned environments, and reusable code.

