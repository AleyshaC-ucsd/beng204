# BENG 204- Group 5
Code and notebooks made for BENG 204 project <br/>
#### Title: Transcriptional Profiling of Tumor Microenvironment and Progression in Pediatric and Adult Glioma <br/>
Authors: Aleysha Chen, Kimmy Wennerholm, Yuhong Zhang, Jason Xu

## Bulk RNA-seq Datasets
Bulk RNA-seq analysis focused on the following datasets:<br/>
* **Chinese Glioma Genome Atlas (CGGA) & St. Jude’s Cloud Platform (SJC)** <br/>
Patients: 3 datasets ; 161 pediatric (under age 21) and 987 adult samples; primary, recurrent, and secondary LGG and HGG<br/>
* **Cancer Cell Line Encyclopedia (CCLE)** <br/>
Cell lines: 69 cell lines, RMA-normalized mRNA expression data (ENTREZG v15 CDF), sourced from Affymetrix U133+2 arrays<br/>
<br/>
Single-cell RNA-seq analysis focused on the following datasets:<br/>
* **Gene Expression Omnibus (GEO) hosted by The National Center for Biotechnology Information website** <br/>
Patients: 21 peds samples (5 HGG, 13 LGG, 3 Normal); 8 adult samples from 4 patients (HGG and Normal for each)<br/>
Cell lines: 8 total samples (6 HGG - LGG85, LGG349, BT138, BT237, BT54, BT88; 2 LGG - LGG275, LGG336)<br/>
  

## Differential expression and pathway enrichment analyses of bulk RNA-seq (CGGA, SJC, CCLE)
**Packages:** DESeq2, limma <br/>
Refer to "Adult_ped_glioma_bulkRNAseq.Rmd" for code used in differential expression analyses on patients. *(Author: Aleysha)*<br/>
Refer to "LGG_vs_HGG.ipynb" for code used in LGG vs. HGG differential expression analysis on cell lines. *(Author: Yuhong)*<br/>
Pathway enrichment was conducted separately using Gene Set Enrichment Analysis (GSEA) and Cytoscape visualization of differential expression marker outputs. *(Aleysha)*

## scRNA-seq analysis of tumor composition and differential expression markers (GSE249263, GSE162631, GSE263796)
**Packages:** Seurat <br/>
Refer to "BENG204Project.Rmd" for code used in scRNA-seq and differential expression analyses on patients. *(Author: Kimmy)*<br/>
Refer to "BENG204HGGLGG.Rmd" for code used in scRNA-seq analysis on cell lines. *(Author: Jason)*<br/>
