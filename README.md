# **In-depth proteomic profiling of gastric cancer tumor cells uncovers previously unidentified signaling proteins**

Chunhui Gu1, 2, Yining Cai2, Fu-Chung Hsiao2, Jennifer Dennison2, Jody Vykoukal2, Johannes Farhmann2, Kim-Anh Do1, Hiro Katayama2, Ehsan Irajizad 1, 2, Samir Hanash2\*

1\. The University of Texas MD Anderson Cancer Center, Department of Biostatistics

2\. The University of Texas MD Anderson Cancer Center, Department of Clinical Cancer Prevention

This is the analysis code repositories for the above publication.

The code is organized into three major parts.

1.  rna_seq_analysis.Rmd contains code about RNA data preprocessing/exploration

2.  gastric_primary_cell_correlation_analysis.rmd contains code about most analyses in this publication. It includes protein-RNA-data matching and association analysis between RNA expression and protein expression.

3.  missing-protein-unique-peptide contains code for checking the distribution of unique peptides of identified missing proteins in gastric_primary_cell_correlation_analysis.rmd.

The corresponding pdf version of those three RMarkdown files are added for an easy way to check the output of those codes.

The code provided in this repository plus the data should be enough to replicate all the results in this publication, except for tissue-specificity analysis which has to be manually done within <https://gtexportal.org/home/multiGeneQueryPage> with the list of identified 177 missing proteins.

Ideally, the code should be run in the following order:

1.  rna_seq_analysis.Rmd

2.  gastric_primary_cell_correlation_analysis.rmd

3.  missing-protein-unique-peptide

4.  cancer-specificity-analysis
