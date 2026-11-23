# Final Year Project – BS Bioinformatics

## Microarray-Based Expression Profiling for Identification of Differentially Expressed Genes and Related Pathways in Breast Cancer

**Student:** Sayeda Rehmat  
**Degree:** BS Bioinformatics  
**University:** Virtual University of Pakistan  
**Department:** Biological Sciences  
**Project Supervisor:** Saddia Bano  
**Project Type:** Final Year Project (FYP)

---

## About the Project

This repository contains my Final Year Project, completed as part of my BS Bioinformatics degree at Virtual University of Pakistan.

The project was based on studying gene expression differences between breast cancer and normal breast tissue using microarray data. The main purpose was to identify differentially expressed genes (DEGs) and explore the biological pathways associated with these genes.

For this study, I used a publicly available dataset from the NCBI Gene Expression Omnibus (GEO) database. I worked with the GSE15852 dataset, which contains gene expression data from breast tumor and normal tissue samples.

During this project, I worked on expression data analysis, sample quality assessment, visualization of results, identification of differentially expressed genes, and pathway enrichment analysis. I also explored the biological roles of some genes identified in breast cancer-related pathways.

## Project Objectives

The project had two main objectives:

1. To identify differentially expressed genes between breast tumor and normal tissue samples.
2. To identify biological pathways associated with the differentially expressed genes.

## Dataset

The data used in this project was obtained from the NCBI Gene Expression Omnibus (GEO).

| Dataset information | Details |
|---|---|
| GEO Accession | GSE15852 |
| Data source | NCBI GEO |
| Platform | Affymetrix Human Genome U133A Array |
| Breast tumor samples | 43 |
| Normal samples | 43 |
| Total samples | 86 |

**Dataset link:** [GSE15852 – NCBI GEO](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE15852)

## What I Did

I followed a step-by-step approach to analyze the microarray gene expression data.

### 1. Data Collection

I obtained the GSE15852 dataset from the GEO database. The dataset included 43 breast tumor samples and 43 normal samples.

### 2. Quality Control and Normalization

I examined the expression data using box plots to check the distribution of values across samples.

Normalization was performed to make the expression distributions more comparable between samples before further analysis.

### 3. Data Visualization

I used different plots to understand the expression data and observe differences between the tumor and normal groups.

The visualizations included:

- **Box Plot:** To examine the distribution of gene expression values across samples.
- **UMAP Plot:** To visualize the expression patterns and observe how tumor and normal samples were distributed.
- **Volcano Plot:** To visualize genes showing increased or decreased expression along with their statistical significance.
- **VOOM Plot:** To examine the relationship between average expression and variance in the data.

### 4. Differentially Expressed Gene Analysis

I compared gene expression between breast tumor and normal samples to identify differentially expressed genes.

The analysis used the following thresholds, as reported in my project:

- p-value less than 0.05
- Fold change less than -1 or greater than 1

Based on these criteria, the analysis reported **22,283 differentially expressed genes**.

The volcano plot was used to visualize the expression changes:

- Red points represented upregulated genes.
- Blue points represented downregulated genes.

### 5. Pathway Enrichment Analysis

After identifying the differentially expressed genes, I performed pathway enrichment analysis using Enrichr.

The purpose was to explore which biological pathways were associated with the identified genes and to understand their possible relevance to breast cancer.

## Results

### Differentially Expressed Genes

The analysis reported 22,283 differentially expressed genes in the GSE15852 dataset using the selected thresholds.

The volcano plot provided a visual representation of genes with increased and decreased expression between the two sample groups.

The UMAP plot also showed differences in the distribution of tumor and normal samples.

### Pathway Enrichment Results

The pathway enrichment analysis highlighted several cancer-related pathways.

The main results included:

| Pathway | Number of genes |
|---|---:|
| Pathways in cancer | 85 |
| Breast cancer | 26 |
| Proteoglycans in cancer | 49 |

### Some Genes Identified in the Analysis

The following genes were among those examined in the breast cancer pathway results:

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

I also explored the biological functions of these genes, particularly their roles in cell-cycle regulation, Wnt signaling, estrogen signaling, and growth-related pathways.

## Discussion

One interesting part of this project was exploring how different genes are involved in biological processes related to breast cancer.

For example:

- **CDK4** is involved in cell-cycle regulation and cell division.
- **FZD4** and **LEF1** are associated with Wnt signaling.
- **ESR1** is related to estrogen receptor signaling.
- **RB1** plays a role in controlling cell division.
- **ERBB2** is involved in cell growth and signaling.

Studying these genes helped me understand how changes in gene expression can be related to different molecular processes in breast cancer.

The results also showed the importance of looking at biological pathways rather than focusing only on individual genes.

## Conclusion

Through this Final Year Project, I analyzed microarray gene expression data to study differences between breast cancer and normal tissue samples.

The analysis helped identify differentially expressed genes and explore their associated biological pathways. Several cancer-related pathways and genes involved in important cellular processes were highlighted.

Overall, this project gave me practical experience in working with public gene expression datasets, understanding differential gene expression, visualizing biological data, and performing pathway enrichment analysis.

It also helped me develop a better understanding of how bioinformatics approaches can be used to study the molecular aspects of cancer.

## Tools and Resources

The main resources and tools used in this project included:

- **NCBI GEO:** For obtaining the gene expression dataset.
- **Affymetrix Human Genome U133A Array:** Microarray platform used for the dataset.
- **Enrichr:** For pathway enrichment analysis.
- **Data visualization:** Box plots, UMAP plots, volcano plots, and VOOM plots.

## Limitations

- The study was based on a single publicly available dataset.
- The findings were based on computational analysis.
- The identified genes and pathways require further validation before any clinical application.
- The results depend on the dataset and statistical thresholds used in the analysis.

## Acknowledgements

I would like to thank my project supervisor, **Saddia Bano**, for her guidance and support throughout my Final Year Project.

I am also thankful to the Department of Biological Sciences, Virtual University of Pakistan, and NCBI GEO for providing access to publicly available gene expression data.

---

**Academic Project:** BS Bioinformatics Final Year Project  
**University:** Virtual University of Pakistan  
**Department:** Biological Sciences
