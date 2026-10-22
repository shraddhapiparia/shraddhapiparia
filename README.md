Hi, I’m Shraddha Piparia — Computational Biologist with a PhD in computer science 👋  

I build machine learning models and analysis pipelines for genomics, proteomics and single-cell data, mostly on questions of disease heterogeneity and treatment response in asthma and long COVID.

Computational Biology + ML | Genomics, Proteomics & Single-Cell Multi-omics

[Personal site](https://shraddhapiparia.github.io/) · [Publications](https://scholar.google.com/citations?user=T3k1qhwAAAAJ&hl=en&oi=ao) · [Write-ups](https://shraddhapiparia.github.io/articles.html)

---

## Tech Stack

**ML/DL**: PyTorch · Representation Learning · VAEs · Transformers · SHAP · Clinical NLP

**Computational Biology**: GWAS · Disease heterogeneity · Single-cell · Multi-omics · UK Biobank · Olink  

**Engineering**: Nextflow · Docker · Spark · SLURM · GitHub Actions  

---

## Featured Projects

### [Genotype representation learning](https://github.com/shraddhapiparia/LD-aware-genotype-embeddings) (in progress)

Does a nonlinear encoder trained on genotypes alone capture more phenotype-relevant signal from an LD block than PCA at the same dimensionality, and is any gain specific to asthma regions?

- Per-block β-VAE with an ordinal decoder, compared against per-block PCA with matched latent dimension, across 464 blocks from asthma and control regions.
- Cross-block embedding and phenotype evaluation (held-out partial R², primary phenotype IgE) is under way.

### [Pediatric and adult long COVID proteomics](https://github.com/shraddhapiparia/proteomics_npx_analysis)

Do children with neurological long COVID have a distinct inflammatory plasma protein profile, and does it hold in adults?

- Olink NPX data from 111 children at two centers. Defined the neurological long COVID group and the comparator design; handled center confounding with ComBat while keeping the primary comparison within a single site.
- Candidate proteins (FGF21, TNFRSF11B, IL17C, CCL2) tested with permutation-based inference; tested replication in more than 50,000 UK Biobank adults using WHO-aligned symptom definitions and a Spark pipeline.
- Manuscript submitted (2026).

### [Single-cell RNA + ATAC multiome](https://github.com/shraddhapiparia/sc-rna-atac-multiome-analysis) (in progress)

Does adding chromatin accessibility improve how well cell identity and state are resolved in PBMCs compared with RNA alone?

- RNA and ATAC processed separately, then combined with weighted nearest neighbor integration in Seurat/Signac. The first ATAC LSI component tracked sequencing depth (ρ ≈ 0.92), so it was excluded from integration.
- Clusters checked against technical QC metrics and annotated with SingleR plus canonical markers.
- Next: motif activity (chromVAR), gene activity, and peak-to-gene links.

### [Endotype-specific asthma GWAS](https://github.com/shraddhapiparia/ANOVA-like-GWAS-NextFlow)

Do clinically defined asthma endotypes have genetic associations that a case-control GWAS misses?

- Defined endophenotypes from lung function and treatment response with PCA, then tested variants with ANCOVA-style models. Discovery in CAMP, validation in GACRS. Nextflow pipeline for SLURM.
- Piparia S, et al. *A principal component analysis-based endophenotype definition for change in lung function and inhaled corticosteroid treatment response in childhood asthma.* Respiratory Research 26:351 (2025). [DOI](https://link.springer.com/article/10.1186/s12931-025-03426-z)
- Piparia S, et al. *A categorical ANCOVA approach to severity endophenotype-specific GWAS in childhood asthma.* Journal of Personalized Medicine 16(1) (2026). [DOI](https://www.mdpi.com/2075-4426/16/1/32)

### [miRNA modifiers of inhaled corticosteroid response](https://github.com/shraddhapiparia/miRNA_ics_interaction)

Which circulating miRNAs modify how children with asthma respond to inhaled corticosteroids?

- miRNA × treatment interaction models in childhood asthma cohorts; identified miR-584-5p and miR-205-5p as a candidate modifiers of corticosteroid resistance.
- Piparia S, et al. *MicroRNA-584-5p as a key modulator of inhaled corticosteroid resistance in asthma.* AJRCCM 211 Suppl 1 (2025). [DOI](https://academic.oup.com/ajrccm/article-abstract/211/Supplement_1/A5441/8336421)

### [COVID-19 from pediatric radiology reports](https://github.com/shraddhapiparia/COVID-Radiology-Study)

Can the text of chest X-ray impressions alone identify children with COVID-19?

- NLP features from more than 2,500 radiology impressions, random forest classifier, SHAP for interpretation.
- Piparia S, Defante A, Tantisira K, Ryu J. *Using machine learning to improve our understanding of COVID-19 infection in children.* PLOS ONE 18(2): e0281666 (2023). [DOI](https://doi.org/10.1371/journal.pone.0281666)

### [From FASTQ to asthma GWAS](https://github.com/shraddhapiparia/from-fastq-to-asthma-gwas)

A modular template covering read QC, alignment, variant calling, GWAS, polygenic risk scores and eQTL lookup.

