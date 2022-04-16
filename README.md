# Report on Music Diversity and Circulation in Europe

This repo is created for two deliverables. Please use the following structure.

1. [Report on Music Diversity and Circulation in Europe](https://zenodo.org/record/6465114#.YlsMz9pBzIU) [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.6465114.svg)](https://doi.org/10.5281/zenodo.6465114)

2. [Music diversity and circulation: Novel data collection methods and indicators](https://doi.org/10.5281/zenodo.6465135) [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.6465135.svg)](https://doi.org/10.5281/zenodo.6465135)



Both follow the [Open Policy Analysis Guidelines](http://www.bitss.org/wp-content/uploads/2019/03/OPA-Guidelines.pdf) and the best practices of the European Union's Knowledge For Policy and the [European Open Science Cloud](https://eosc-portal.eu/) portal.

## Folders

**root** - The two articles, `.bib` bibliography files, and `yml` files for markdown conversions, plus reproducbile `docx`, `pdf`, `epub` versions. Work in the `Rmd` markdown files. If you do not write R code, just ignore the R code chunks, and use it as a clean markdown text.

**bib** - please save here individual BibTex entries.  The consolidated entries will should be placed in one of the main `.bib` files in the root folder. The pandoc / knitr / RStudio workflow can have hickuups with bib files, so try to save individual files first in `bib/xyz.bib`

**not_included** - user's scrap directory, excluded by `.gitignore`.  Please put your non-synchronized scaps and code doodles here.

**data-raw** - data as downloaded, received, as a starting point of our reproducible work. You will find here 5 CAP surveys.

**R** - R code written for the publications.  It is better to write stand-alone R codes, and put final 'chunks' into the `.Rmd` files.

**data** - Final data outputs that will be placed in the articles.



