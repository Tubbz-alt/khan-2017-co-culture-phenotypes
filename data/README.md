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


RNA seq data is available under accession GSE103773:
<https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE103773>

See also BioProject [PRJNA406985](https://www.ncbi.nlm.nih.gov/bioproject/PRJNA406985) and
SRA	[SRP117464](https://www.ncbi.nlm.nih.gov/sra?term=SRP117464).
