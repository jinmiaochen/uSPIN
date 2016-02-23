#uSPIN
=================

###An integrated single cell ordering pipeline
-----------------------------------------
This is a BETA release of uSPIN. An unsupervised cell ordering algorithm designed for single-cell RNA-sequencing data.
To use this package, you will need the R statistical computing environment (R (>= 3.1.2)) and several dependent 
packages (monocle, topGO, VGAM, gplots, ggplot2, parallel, proxy) available through Bioconductor.

------------------------------------------------
### uSPIN Package Installation and Running
1.Download this package to your local directory, then start the R session, and change the working directory to where the "uSPIN_0.0.0.9000.tar.gz" is, then
type the following commands:
```
install.packages("uSPIN_0.0.0.9000.tar.gz", repos = NULL, type = "source")
```  
2.Running this package is depended on several other R packages(listed above) which available through Bioconductor. You need to install them first, or we provide a R script `uSPIN_firstRun.r` 
can help you do that automatically. 
```
library(uSPIN)
source('uSPIN_firstRun.r')
```
3.We provide two real testing datasets (GSE63269 & GSE60783) here, and to run them,
```
source('testing_datasetI.r')
source('testing_datasetII.r')
```
4.Check the help pages for more information about this package and the using of the workhorse function.              
**NOTE**: This package is in the BETA stage of development, new features will continue to be added, please take note for changes in this package. Also this version is tested on windows only.

 
