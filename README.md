# Zwart Lab Tools
A list of tools routinely used by the Zwart lab for genomics analysis and visualization.

## Differential analysis (RNA-seq and ChIP-seq) <a name="differential analysis"></a>

For the basics of differential binding and gene expression and tutorials to guide you through.

**DESeq2 for differential gene expression of RNA-seq experiments:** [https://bioconductor.org/packages/release/bioc/vignettes/DESeq2/inst/doc/DESeq2.html]

**DiffBind for differential binding analysis of ChIP-seq experiments:** [https://bioconductor.org/packages/release/bioc/vignettes/DiffBind/inst/doc/DiffBind.pdf]


## Basic analysis of ChIP-seq data <a name="Basic analysis of ChIP-seq data"></a>

The easiest way to do basic analysis on your ChIP-seq regions of interest without using the RHPC server.

**UCSC Galaxy Cistrome Server for running motif and genomic regions enrichment and lifting over to a different genome build:** [http://cistrome.org/ap/root]

**CistromeDB Toolkit Giggle analysis (hg38 only!!!!):** [http://dbtoolkit.cistrome.org/]



## Visualization of ChIP-seq data <a name="Visualization of ChIP-seq data"></a>

**DeepTools for heamaps and profiles (RHPC server):** [https://deeptools.readthedocs.io/en/develop/]

**EaSeq for heatmaps and profiles (Windows):** [https://easeq.net/]



## General visualization <a name="General visualization"></a>

**ggplot2 in R:** [https://ggplot2.tidyverse.org/, https://r4ds.had.co.nz/data-visualisation.html, http://www.sthda.com/english/wiki/ggplot2-box-plot-quick-start-guide-r-software-and-data-visualization]

**ggpubr in R for statistics in your plot:** [https://rpkgs.datanovia.com/ggpubr/]

**Cool color palettes in R:** [https://github.com/karthik/wesanderson, https://www.datanovia.com/en/blog/top-r-color-palettes-to-know-for-great-data-visualization/]


## Gene set enrichment analysis <a name="gene set enrichment analysis"></a>

If you have differential expression data, first run differential gene expression analysis, then rank ALL your genes by log2FC x padj to be the most stringent. Then use the ranked gene list as input.

**GSEA with DOSE and clusterProfiler in R:** [http://yulab-smu.top/clusterProfiler-book/chapter2.html#gene-set-enrichment-analysis, http://yulab-smu.top/clusterProfiler-book/chapter12.html#running-score-and-preranked-list-of-gsea-result]

If you have a list of genes of interest which are not ranked (eg from connecting AR binding to closest genes) use the enricher function of clusterProfiler with gene sets (like MSigDB from the Broad).

**Hypergeometric enrichment test with clusterProfiler in R:** [http://yulab-smu.top/clusterProfiler-book/chapter3.html#msigdb-analysis]

## Exploration <a name="exploration"></a>

Once you have a gene or genes of interest, you can explore the data available (eg gene expression, mutation, copy number variation and clinical characteristics) in public cancer datasets.

**cBioPortal:**  [https://www.cbioportal.org/]


## Getting help and tutorials <a name="getting help and tutorials"></a>

You can always ask your local professionals. In addition, here are some useful pointers for where to look for help online. 

**Biostars -- Many times your bioinformatic question has already been answered online:** [https://www.biostars.org/]

**BioConductor walk through of RNA-seq exploratoration and differential analysis at the gene-level** [https://bioconductor.org/packages/release/workflows/vignettes/rnaseqGene/inst/doc/rnaseqGene.html]

**Unix tutorial for basic commands on the RHPC server** [http://www.ee.surrey.ac.uk/Teaching/Unix/unix1.html, http://www.ee.surrey.ac.uk/Teaching/Unix/unix2.html]

