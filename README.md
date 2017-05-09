## TITLE OF YOUR PAPER GOES HERE
### David Jansen
YOUR PAPER'S ABSTRACT GOES HERE
### Scaling up
Scaling up.The advantage of the dual-index approach is that a large number of samples can be sequenced using a number of primers equal to only twice the square root of$

### Figure 4 legend
Principal coordinate ordination of ϴYC values (28) relating the community structures of the fecal microbiota from 12 mice collected on days 0 through 9 (Early) and day$

### Data downloads
Data was downloaded on may 8th using wget.

#### Raw sequence data
http://www.mothur.org/MiSeqDevelopmentData.html

#### References 
SILVA-based bacterial reference alignment https://mothur.org/w/images/9/98/Silva.bacteria.zip
mothur-formatted version of the RDP training set (v.9) https://mothur.org/w/images/5/59/Trainset9_032012.pds.zip

#### Mothur download
version 1.39.5
https://github.com/mothur/mothur/releases/download/v1.39.5/Mothur.linux_64.zip


### Overview

	project
	|- README          # the top level description of content (this doc)
	|- CONTRIBUTING    # instructions for how to contribute to your project
	|- LICENSE         # the license for this project
	|
	|- submission/
	| |- study.Rmd    # executable Rmarkdown for this study, if applicable
	| |- study.md     # Markdown (GitHub) version of the *.Rmd file
	| |- study.tex    # TeX version of *.Rmd file
	| |- study.pdf    # PDF version of *.Rmd file
	| |- header.tex   # LaTeX header file to format pdf version of manuscript
	| |- references.bib # BibTeX formatted references
	| |- XXXX.csl     # csl file to format references for journal XXX
	|
	|- data           # raw and primary data, are not changed once created
	| |- references/  # reference files to be used in analysis
	| |- raw/         # raw data, will not be altered
	| |- mothur/      # mothur processed data
	| +- process/     # cleaned data, will not be altered once created;
	|                 # will be committed to repo
	|
	|- code/          # any programmatic code
	|
	|- results        # all output from workflows and analyses
	| |- tables/      # text version of tables to be rendered with kable in R
	| |- figures/     # graphs, likely designated for manuscript figures
	| +- pictures/    # diagrams, images, and other non-graph graphics
	|
	|- exploratory/   # exploratory data analysis for study
	| |- notebook/    # preliminary analyses
	| +- scratch/     # temporary files that can be safely deleted or lost
	|
	+- Makefile       # executable Makefile for this study, if applicable


### How to regenerate this repository

#### Dependencies and locations
* Gnu Make should be located in the user's PATH
* mothur (v1.XX.0) should be located in the user's PATH
* R (v. 3.X.X) should be located in the user's PATH
* etc.


#### Running analysis

```
git clone https://github.com/SchlossLab/LastName_BriefDescription_Journal_Year.git
make write.paper
```

