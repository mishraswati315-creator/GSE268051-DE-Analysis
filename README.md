# GSE268051 Differential Expression Analysis

An R-based computational pipeline utilizing `limma` and `GEOquery` to perform differential gene expression analysis on the GSE268051 dataset.

## Pipeline Highlights
- **Data Acquisition:** Automated fetching of GEO matrix files.
- **Statistical Modeling:** Linear modeling and empirical Bayes moderation (`eBayes`) for robust p-value calculation.
- **Feature Extraction:** Isolation of significantly Upregulated and Downregulated genes.
- **Visualization:** Generation of high-resolution Volcano Plots, sample distribution Boxplots, and hierarchical clustering Heatmaps.
