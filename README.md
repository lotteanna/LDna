R-package: LDna
-------------

Linkage disequilibrium (LD) network analyses (LDna) is used to find clusters of loci in high  (LD) from population genomic data sets (Kemppainen et al., unpublished). It proviedes a means to partition a pouplation genomics data into sets of loci that bear similar population genetic signals and can for instance be used to *in silico* identify inversion polymorphism and identify loci involved in local adaptation (Kemppainen et al., unpublished). As it only requires a matrix of pariwise LD values it is particularly useful for non-model species where closely related and well-characterised reference genomes are not available.

Current beta version is 0.57.

###Installing

With **devtools** (accessible from CRAN) LDna can be installed by:
```r
devtools::install_github("petrikemppainen/LDna")
```
This downloads the source directly from **github** and builds the vignettes and thus requires LaTeX to be installed on your computer.

Alternatively, download the source file directly an install by:
```r
install.packages("/path_to/source_file", repos = NULL, type = "source")
```
Please install and follow package documentation (includes two tutorials) for more information.