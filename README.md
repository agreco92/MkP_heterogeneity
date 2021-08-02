Code to reproduce RNA-seq analysis contained in [Morcos et al.,2021](https://www.biorxiv.org/content/10.1101/2020.08.21.261552v1.full).



### structure

* bin: code to reproduce the analysis
* docs: gene sets used to score hematopoietic lineages across single cells
* notbooks_html: html-rendered versions of code contained in bin/
* renv.lock: lockfile to recreate R environment using ```Renv```

_Note: as reported [here](https://stackoverflow.com/questions/57895993/knitting-in-r-markdown-file-stops-without-printing-error-when-hitting-a-python-c) , knitting using Python chunks in reticulate is not always effective. To workaround the issue, you can move to the directory containing the notebooks and knit them using_ ```rmarkdown::render('<yourfavouritenotebook.Rmd>'```
