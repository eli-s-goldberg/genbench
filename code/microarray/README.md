# microarray benchmarks
#### boilerplate disclaimer :)
__As for other benchmarks, we are deliberately avoiding *"(pre-)processing"* steps, instead focussing on statistic analyses typical for this datatype. We do not endorse any of the methods used as *"standards"* or *"recommended"*, in fact, because we aim to start simple and avoid as far as possible non-essential packages, methods may very much not recommended. Future updates will implement more advanced methods, i.e. code and datasets are simply intended to represent good, ecologically viable tests of performance. Suggestions for datasets or methods are welcome.__

Benchmark for expression data (microarray), differential expression.

Data
-----------
http://www.ncbi.nlm.nih.gov/sites/GDSbrowser?acc=GDS5070
http://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE45417
(Ramsey and Fontes, 2013)[http://www.ncbi.nlm.nih.gov/pubmed/23954399]
(full article)[http://www.ncbi.nlm.nih.gov/pmc/articles/PMC3783546/]


Code
-----------
- data loading
- processing as according to (limma manual)[http://www.bioconductor.org/packages/release/bioc/vignettes/limma/inst/doc/usersguide.pdf]
    - scale and normalise
    - filter
    - fitting linear model
    - extraction of top differentially expressed genes

Aims
-----------
- "Chocolate" R code, using as little additional data containers as possible

- "Native" R code, written for clarity and function (a la Analyst) rather than optimization and performance

- clock timings for data loading, distance matrix calculation and various clustering methods