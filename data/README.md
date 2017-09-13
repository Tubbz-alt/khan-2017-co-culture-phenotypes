# Data

### Processed data

```
info.48 <- read.csv("../data/Condition_Info_HL_48.csv") #info of treatments and replicates
info.58 <- read.csv("../data/Condition_Info_HL_58.csv") #info of treatments and replicates

grow <- read.csv("../data/Growth.2.csv")                #growth curves and GFP-enabled FACS data

an.48 <- read.csv("../data/HL_48_Neat.csv")             #gene annotation file for HL-48
an.58 <- read.csv("../data/HL_58_Neat.csv")             #gene annotation file for HL-58

raw.48 <- read.csv("../data/HL48_Raw_Counts.csv")       #raw gene rollup counts for HL-48
raw.58 <- read.csv("../data/HL58_Raw_Counts.csv")       #raw gene rollup counts for HL-58

meta <- read.csv("../data/Metabolites.2.csv")           #NMR metabolites and associated metadata
```

### Raw data

<!--
Genetic sequencing data is available on Zenodo for both [16S amplicons](https://zenodo.org/record/803376) and [18S amplicons](https://zenodo.org/record/803476).
-->
