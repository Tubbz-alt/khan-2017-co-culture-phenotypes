# Analysis

These scripts were used to process the data and produce the graphs.

<!--
### 16S_scripts and 18S_scripts

MiSeq reads from 16S and 18S amplicons were processed separately. The two
`*scripts` folders contain simple bash scripts for upstream processing using
a combination of [Qiime 1.9.1](https://github.com/biocore/qiime) and
[VSEARCH](https://github.com/torognes/vsearch). These scripts were used to
cluster and annotate OTUs and build the two `.biom` tables in the [two data folders](https://github.com/pnnl/bernstein-2017-productivity-and-diversity-2/tree/master/data/).

The file `18S_joining.xlsx` shows the output of `vsearch --fastq_stats` when run
on the 18S reads, along with simple graphs. This was used to find ~~optimal~~
reasonable settings for processing these raw reads.

-->

### Figures and Statistics

Elements of published figures are shown in the `figures` folder. These are part
of the output of the `.Rmd` script, which also could render `.docx` and `.html`
files.


### Genes_discussed_in_paper

Genes identified as significantly differentially abundant by DESeq2. There are
also shown in the volcano plots (Figure 3). These files aided in annotation.

### RNA_seq_outputs

All DESeq2 results. In contrast to `genes_discussed_in_paper`, no filtering has
been used and all results are included.


### hetero_cocult_sup.* files

Downstream analysis and graphs for this project are shown in the `.Rmd` file.
These make heavy use of [ggplot2](http://ggplot2.tidyverse.org/) and
[DESeq2](https://bioconductor.org/packages/release/bioc/html/DESeq2.html).

To increase reproducibility, the [Microsoft R Open](https://mran.microsoft.com/open/)
and the [checkpoint package](https://mran.microsoft.com/documents/rro/reproducibility/#timemachine)
are used.
