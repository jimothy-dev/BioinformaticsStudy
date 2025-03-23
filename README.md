# Bioinformatics Analysis: An analysis of knockout method’s impact on resulting differentially expressed genes (DEGs) from bulk gene knockout RNA-seq data

The RNA-seq data used in this analysis was provided by **Morphic**, which supplied the datasets and study context for our research. We performed downstream analysis and visualization using R within a JupyterHub environment.

This report examines the impact of individually knocking out four genes—MXD1, RUNX1, NCOA3, and BHLHE40—on the expression of other genes by identifying differentially expressed genes (DEGs) through DESeq2 analysis. The study compares DEG profiles across three experimental conditions: KO vs. WT, CE vs. WT, and PTC vs. WT. DESeq2 is used to identify DEGs, and visualizations are generated to illustrate gene expression changes and highlight differences among the groups.

## Repository Structure

- `r_analysis/BioinformaticsCode.ipynb`: Main notebook containing all R code. This notebook performs the analysis and generates a PDF with volcano plots for each gene analyzed.
- `data/`: Input datasets required to run the notebook.
- `paper/BioinformaticsAnalysis.docx`: Final report detailing the analysis and results.

## How to Run

1. Clone the repository  
2. Upload the contents of this repo (including the notebook and CSV files) into your JupyterHub environment  
3. Open `r_analysis/BioinformaticsCode.ipynb` in Jupyter  
4. Run all cells to execute the analysis and generate results

**Note:** This project was developed and tested in a JupyterHub environment. It can also be run locally using any environment that supports R notebooks (e.g., VS Code with Jupyter extension or RStudio with the appropriate plugins), provided all required packages are installed and paths are preserved.

## Tools Used

- **R** in **JupyterHub**
- Packages: `BiocManager`, `ggplot2`, `ggrepel`, `UpSetR`, `DESeq2`, `sva`, `rtracklayer`, `GenomicRanges`
- GitHub for version control

## Authors

- Conner Webber, James Simpson, Austin Maggert, Lindsay Ding

