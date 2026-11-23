# Microarray-Based Expression Profiling for Identification of Differentially Expressed Genes and Related Pathways in Breast Cancer

## About the Project

This project focuses on studying gene expression patterns in breast cancer using microarray data. The main aim was to identify genes that show different expression levels in breast tumor samples compared with normal breast tissue and to explore the biological pathways associated with these changes.

Gene expression analysis helps us understand how changes in gene activity may be involved in cancer development and progression. By studying thousands of genes simultaneously, microarray technology provides a broader view of the molecular changes taking place in cancer cells.

For this study, I used publicly available breast cancer microarray data from the Gene Expression Omnibus (GEO) database and performed differential gene expression and pathway enrichment analysis.

## Project Objectives

The study was carried out with two main objectives:

1. To identify differentially expressed genes (DEGs) between breast cancer and normal tissue samples.
2. To identify biological pathways associated with the differentially expressed genes.

## Dataset Information

The dataset used in this project was obtained from the NCBI Gene Expression Omnibus (GEO) database.

| Information | Details |
|---|---|
| Dataset accession | GSE15852 |
| Data source | NCBI GEO |
| Platform | Affymetrix Human Genome U133A Array |
| Breast tumor samples | 43 |
| Normal samples | 43 |
| Total samples | 86 |

**Dataset link:** [GSE15852 – GEO Database](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE15852)

## Methodology

The analysis followed a series of steps, starting with dataset collection and ending with biological interpretation.

### 1. Dataset Collection

Microarray expression data for breast tumor and normal samples were obtained from the GEO database using accession GSE15852.

### 2. Quality Control and Normalization

Quality control was performed to examine the expression data and assess sample consistency.

Normalization was used to make expression distributions comparable across samples, reducing technical variation before further analysis.

### 3. Exploratory Data Analysis

A UMAP plot was generated to visualize similarities and differences between tumor and normal samples.

The plot showed a degree of separation between the two groups, suggesting differences in their gene expression profiles.

### 4. Differential Gene Expression Analysis

Differential expression analysis was performed to identify genes showing expression differences between breast tumor and normal samples.

The thresholds reported in the analysis were:

- p-value < 0.05
- Fold change < -1 or > 1

Genes meeting the selected criteria were considered differentially expressed.

### 5. Data Visualization

Different plots were used to examine and present the analysis results:

- **Box Plot:** Used to examine expression distributions across samples after normalization.
- **UMAP Plot:** Used to visualize sample-level expression patterns.
- **Volcano Plot:** Used to display the statistical significance and magnitude of gene expression changes.
- **VOOM Plot:** Used to examine the mean-variance relationship in the expression data.

### 6. Pathway Enrichment Analysis

Pathway enrichment analysis was performed using Enrichr to investigate the biological pathways associated with the identified genes.

The analysis focused on understanding how the differentially expressed genes relate to breast cancer and other cancer-associated biological processes.

## Results

### Differentially Expressed Genes

The analysis identified **22,283 differentially expressed genes** in the GSE15852 dataset using the thresholds reported in the study.

The volcano plot showed genes with increased and decreased expression levels:

- Red points represent upregulated genes.
- Blue points represent downregulated genes.

### Pathway Enrichment Analysis

The pathway enrichment analysis highlighted several cancer-related pathways.

| Enriched pathway | Number of genes |
|---|---:|
| Pathways in cancer | 85 |
| Breast cancer | 26 |
| Proteoglycans in cancer | 49 |

These findings show that the identified genes are associated with biological pathways relevant to cancer.

### Genes of Interest

Some of the genes identified in the breast cancer pathway analysis included:

| Gene | Log2 Fold Change |
|---|---:|
| FZD4 | 0.629876 |
| LEF1 | 0.423752 |
| ESR1 | 0.244603 |
| JUN | 0.168994 |
| CDK4 | 0.098931 |
| ERBB2 | -0.248987 |
| RB1 | -0.226344 |
| FGFR1 | -0.147828 |

These genes are involved in different biological processes, including cell-cycle regulation, Wnt signaling, estrogen signaling, and growth-factor signaling.

## Discussion

The results provided an overview of gene expression changes and their possible biological relevance in breast cancer.

Several genes were particularly interesting:

- **CDK4:** Involved in cell-cycle regulation and cell proliferation.
- **FZD4:** Associated with Wnt signaling, which plays a role in cell growth and development.
- **LEF1:** A transcription factor involved in Wnt/β-catenin signaling.
- **ESR1:** Encodes estrogen receptor alpha and is associated with estrogen-related signaling.
- **RB1:** A tumor suppressor gene involved in controlling cell division.
- **ERBB2:** Encodes HER2, a receptor involved in cell growth and signaling.

The findings highlight the involvement of multiple signaling pathways rather than a single gene or biological process.

## Conclusion

This project used microarray-based gene expression analysis to investigate molecular differences between breast cancer and normal breast tissue.

The analysis identified differentially expressed genes and highlighted associated biological pathways, including breast cancer, general cancer pathways, and proteoglycans in cancer.

Overall, the study provided an opportunity to explore how computational gene expression analysis can help investigate the molecular mechanisms underlying breast cancer and identify potential directions for future biomarker research.

## Tools and Resources

The following resources were used in the project:

- **NCBI GEO:** For obtaining publicly available microarray expression data.
- **Affymetrix Human Genome U133A Array:** Microarray platform associated with the dataset.
- **Enrichr:** For pathway enrichment analysis.
- **Data visualization:** Box plots, UMAP plots, volcano plots, and VOOM plots.

## Limitations

- The study was based on one publicly available microarray dataset.
- The findings represent computational analysis and require further experimental validation.
- Differential expression results depend on the selected statistical thresholds.
- The identified genes and enriched pathways should be considered research findings rather than clinically validated biomarkers.

## Acknowledgements

I would like to acknowledge my project supervisor, **Saddia Bano**, and the Department of Biological Sciences, Virtual University of Pakistan, for their guidance and support throughout this final-year project.

I also acknowledge the NCBI Gene Expression Omnibus for making publicly available gene expression data accessible to researchers.

---

**Project:** Final Year Project – BS Bioinformatics  
**University:** Virtual University of Pakistan  
**Department:** Biological Sciences  
**Supervisor:** Saddia Bano  
**Student:** Sayeda Rehmat
