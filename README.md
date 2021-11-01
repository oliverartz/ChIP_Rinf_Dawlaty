# ChIP_Rinf_Dawlaty
This is a first stab at analyzing ChIPseq data. The data was taken from a publication entitled "Rinf Regulates Pluripotency Network Genes and Tet Enzymes in Embryonic Stem Cells" (Ravichandran et al., 2019) and published in Cell Reports.

https://doi.org/10.1016/j.celrep.2019.07.080

I tried to stick to the analysis performed in the publication as much as I could. However, some parameters, e.g. quality cutoffs, were not described. Hence, my results are not fully identical with the published results. Quality control steps were largely omitted. All data and analysis tools are publicly available.

The analysis was performed in the cloud using Google Colab. Since the storage of the used instance was too low for the dataset, I mounted my Google Drive to accomodate for the lack in storage capacity. Most analyses after peak calling were performed on a local machine using R (in R Studio).

File descriptions:
- 20211030_ChIPseq_Rinf_Meelad.ipynb: Jupyter notebook used for data analysis on Google Colab.
- analysis.Rmd: R markdown file used for data analysis in RStudio on the local machine.
- analysis.html: Knitted report from the R markdown file
