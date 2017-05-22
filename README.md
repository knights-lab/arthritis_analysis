# arthritis_analysis
Code for the analysis of the IBD and arthritis data

Steps for Acquiring the Data:
1. Run shiz
2. Run emb15 and embalmulate pipeline
3. Run src/run_kegg_annotations.sh

For this analysis, I assumed that the aforementioned steps were already complete.

Purpose of this repository is to:
1. Run Kruskal-Wallis comparisons on KEGG table
2. Pairwise non-parametric (Mann-Whitney, Wilcoxon) between each groups KEGGs

Steps in the works
* Summary Statistics
  * Are there confounders(age, BMI, sex) between groups
* Taxonomy tables
** Species and Genus
** Bray-Curtis PCoA
** Adonis
* Kegg Table
** Kruskal-Wallis
** Mann-Whitney (Wilcoxon)
