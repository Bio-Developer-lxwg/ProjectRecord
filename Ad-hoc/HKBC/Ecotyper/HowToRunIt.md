### Website-based Run
* Need to remove the duplicate gene from gene expression table
* File used
  * /home/lixin/lxwg/ad-hoc/Ecotyper/HKBC/all.231tumor.normal.renamed.no.dup.txt

### R-command-line-based Run
1: Dependent packages
```
Official website:
R packages: , NMF (v0.21.0 and v0.23.0), RColorBrewer (v1.1.2), cluster (v2.1.0 and v2.1.2)), circlize (v0.4.10 and v0.4.12), cowplot (v1.1.0 and v1.1.1), 
data.table (base package R v3.6.0 and v4.1.0), doParallel (v1.0.15 and v1.0.16), ggplot2 (v3.3.2, v3.3.3), grid (base package R v3.6.0 and v4.1.0), 
reshape2 (v1.4.4), viridis (v0.5.1 and v0.6.1), config (v0.3.1), argparse (v2.0.3), colorspace (v1.4.1 and v2.0.1), plyr (v1.8.6).

How to install dependences 
1: upgrade your R version to 4.x (eg the latest version 4.2.2)
2: Install R packages
bio_pkgs <- c("NMF", "RColorBrewer", "cluster", "circlize", "cowplot", "data.table", "doParallel", "ggplot2", "grid", "reshape2", "viridis", "config", "argparse", "colorspace", "plyr")
BiocManager::install(bio_pkgs)
```

2: Run command line
```
Rscript EcoTyper_recovery_bulk.R -d Carcinoma -m /home/lixin/lxwg/ad-hoc/Ecotyper/HKBC/all.231tumor.normal.renamed.no.dup.txt -t 8 -o /home/lixin/lxwg/ad-hoc/Ecotyper/HKBC/output/EcoTyper_recovery_bulk
```
