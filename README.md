# IRF4 amplifies Th2 response through inhibition of Il31 expression
This code contains the general processing of files to generate data in the Nature Immunology paper, "IRF4 amplifies Th2 response through inhibition of Il31 expression".
The scripts within this directory are separated by assay and analysis, consisting of 1) Cut&run, 2) ATAC-seq, and 3) Single-cell RNA-seq. 
The scripts contain R and Bash code and were run in either a Windows or Linux environment (JupyterLab). Rstudio verion 2025.09.2_418 was used to run scripts. Renv are submitted per analysis section. 

I) Processing of Cut&run data
    1. Preprocessing
    2. Peak calling and annotation
    3. Generation of peak mapping and statistics
    4. Generation of Eulerr diagrams 
II) Processing of ATAC-seq data
    1. Preprocessing
    2. Generation of peak mapping and statistics
III) Single Cell RNA-seq
    1. Preprocessing and generation of Seurat object
    2. Visualization of clustering
