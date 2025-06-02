![Image](https://github.com/user-attachments/assets/3904e458-627d-4330-a45a-3be7809fe8e0)



# 🧬 DNA Methylation Array Data Analysis Pipeline

This repository provides a comprehensive pipeline and curated guidance for the analysis of DNA methylation microarray datasets (e.g., Illumina 450K/850K arrays), spanning from preprocessing to downstream biological interpretation.


> 📖 **Reference**: Karishma Sahoo et al., *Methods in DNA methylation array dataset analysis: A review*, Computational and Structural Biotechnology Journal, 2024.  
> DOI: [10.1016/j.gendis.2024.100366](https://doi.org/10.1016/j.csbj.2024.05.015)

---

## 🔍 Overview

DNA methylation is a key epigenetic modification involved in gene regulation, development, and disease. This repository is designed to guide researchers through each major step of methylation array data analysis:

1. **Data Retrieval & Preprocessing**
2. **Normalization & Batch Correction**
3. **Clustering & Exploratory Analysis**
4. **DMR Identification**
5. **ML/DL Model Development**
6. **Functional Annotation**
7. **Visualization of Epigenomic Insights**

---

## 🧪 Workflow Breakdown

### 1. Preprocessing Analysis
- **Quality Control**: Remove probes with detection p-values < 0.05, SNP-associated probes, and sex chromosomes.
  - Tools: `minfi`, `ChAMP`
- **Normalization Methods**:
  - `pQuantile`, `FunNorm`, `SWAN`, `Noob`, `BMIQ`
- **Other Preprocessing**:
  - Probe type and color adjustment
  - Background subtraction (`poobah`, `danes`)
  - Batch correction (`Combat`, `RUV`)

### 2. Exploratory Clustering
- **Techniques**: PCA, Hierarchical, Consensus Clustering, Fuzzy c-means, DERC, K-means
- **Goal**: Discover sample subgroups and methylation patterns

### 3. Differential Methylation Analysis
- Tools: `limma`, `Bumphunter`, `ANOVA`, `Bayesian hierarchical`, `Univariate beta mixture`
- Identify DMRs/DMPs (Differentially Methylated Regions/Positions)

### 4. ML & DL Applications
- Feature selection using ML algorithms
- Classification with deep neural networks
- Prognostic and diagnostic model development

### 5. Functional Annotation
- Tools: DAVID, Gene Ontology, KEGG Pathway, GSVA
- Goal: Interpret biological relevance of DMRs

### 6. Visualization
- Techniques: Volcano plot, Heatmap, Box plot, Circos plot, Violin plot, Scatter plot

---

