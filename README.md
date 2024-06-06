## A Collection of Proteome Panels and Meta-Data

It gathers protein panel information and meta-data for [pQTLtools](https://github.com/jinghuazhao/pQTLtools).

### Installation

1. Install from R

```r
if (!requireNamespace("remotes", quietly = TRUE)) install.packages("remotes")
remotes::install_github("jinghuazhao/pQTLdata")
```

2. Install from GitHub repository

```bash
git clone https://github.com/jinghuazhao/pQTLdata
R CMD INSTALL pQTLdata
```

3. Install from zip file

```bash
wget https://github.com/jinghuazhao/pQTLdata/archive/refs/heads/main.zip
unzip main
```

### A summary of datasets

```r
library(help=pQTLdata)
help(pQTLdata)
```
