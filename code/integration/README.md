genbench
=======

GenBench: Realworld Genomics Benchmarks for R, forked from and inspired by <a href= "https://github.com/hannesmuehleisen/genbase">GenBase</a>.

integration
------------
Some typical methods/approaches used for integrating different sources of information, for example finding links between a results list (e.g. top differentially expressed genes, etc)

Code
-----------
- igraph.R: a minimal script for extracting/cleaning/and visualising entrez RIF networks, and performing some cocitation analysis
 - further information
  - [gene RIFs](http://www.ncbi.nlm.nih.gov/gene/about-generif)
  - [igraph](http://igraph.sourceforge.net/)
 - load iGraph network object from flat table
 - do some basic analysis/coloring/plotting
 - do some subsetting
  - random 1%
  - limit genes by GO terms (or anything other annotation)
  - limit papers by MeSh terms

- humanLiverCohort.R
 - reproduce aspects of integrative analysis carried out in the Human Liver Cohort project
  - [synapse entry](https://www.synapse.org/#!Synapse:syn299418)
  - [Schadt et al, 2008](http://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.0060107)


