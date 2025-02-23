# scRNA-Seq Training Module

This CCDL-designed module covers the analysis of single-cell RNA-seq data using [Salmon's Alevin](https://salmon.readthedocs.io/en/latest/alevin.html) and [scater/scran](https://bioconductor.org/packages/devel/bioc/vignettes/scran/inst/doc/scran.html) packages.

It depends on knowledge gained in the [Intro to R](https://github.com/AlexsLemonade/training-modules/tree/master/intro-to-R-tidyverse) and analyses are performed within a [Docker container](https://github.com/AlexsLemonade/training-modules/tree/master/docker-install) or on the CCDL RStudio server.
It covers normalization and dimension reduction methods that can be used for both tag-based and full-length single-cell data, as well as the quantification of tag-based scRNA-seq data.

The notebooks that comprise this module are:

* [Quantification of tag-based scRNA-seq data](https://alexslemonade.github.io/training-modules/scRNA-seq/01-scRNA_quant_qc.nb.html)
* [Quality control and filtering ](https://alexslemonade.github.io/training-modules/scRNA-seq/02-filtering_scRNA.nb.html)
* [Normalization](https://alexslemonade.github.io/training-modules/scRNA-seq/03-normalizing_scRNA.nb.html)
* [Dimension reduction](https://alexslemonade.github.io/training-modules/scRNA-seq/04-dimension_reduction_scRNA.nb.html) 
* [Clustering](https://alexslemonade.github.io/training-modules/scRNA-seq/05-clustering_markers_scRNA.nb.html)

This directory also contains pathway analysis modules customized to these data:

* [Overrepresentation analysis](https://alexslemonade.github.io/training-modules/scRNA-seq/06-overrepresentation_analysis.nb.html)
* [Gene set enrichment analysis](https://alexslemonade.github.io/training-modules/scRNA-seq/07-gene_set_enrichment_analysis.nb.html)

Additional exercise notebooks:

* [Quantification](https://github.com/AlexsLemonade/training-modules/blob/master/scRNA-seq/exercise_01-scrna_quant.Rmd)
* [Clustering](https://github.com/AlexsLemonade/training-modules/blob/master/scRNA-seq/exercise_02-scrna_clustering.Rmd)
* [Pathway analysis](https://github.com/AlexsLemonade/training-modules/blob/master/scRNA-seq/exercise_03-scrna-seq_pathway.Rmd)
