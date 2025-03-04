# Analyze-of-scRNA-seq

Project 4 for the Class

This project was completed with two other team members and is stored in the BioByte repository, branch repository_branch. Below is the part that I contributed.

Data Analysis

For this project, I analyzed datasets deposited in the GEO repository (GSE139495, published in 2020).

Data Source:
  GEO Repository (https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE139495
             https://pubmed.ncbi.nlm.nih.gov/32822091/)
  
Due to the large size of the datasets and the time required to initialize the code, I created two notebooks and uploaded in this repository. 

1. Exploratory Data Analysis (EDA), Quality Control, and Merging Final Dataset: This notebook prepares the data for further analysis.
2. scRNA Sequencing Analysis: This notebook contains the analysis of the single-cell RNA sequencing data.

The datasets are too large to upload to the GitHub repository. Please refer to the original site for your references.

Lessons Learned:

Since scRNA-seq data often contains many values close to zero, I realized that imputing data should have been my first step. I learned to use the harmonypy library for data imputation. In future analyses, I will start by imputing the data.

Thank you.

