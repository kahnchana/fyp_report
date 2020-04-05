# FYP Report
Latex based report.  

## Introduction
This template is in accordance to the Final Year Research Project report template provided by the Department of Electronics and Telecommunications Engineering at University of Moratuwa, Sri Lanka. If there are any problems / discrepencies, please create an issue. Do note that this was created by students, and is in no way official. 

## Generating Report

Run the following to compile the report. 

```
latex thesis
bibtex thesis
latex thesis
```

## Structure

All necessary files are inside the directory `main`. The file thesis.bib contains the root structure of the document. The files thesis.bib and defs.bib contain all references and certain definitions respectively. 

The content, ordered by chapter is in separate latex files under the `main/chapters` directory. Figures have been put to a separate directory `main/figs`. You can refer to existing tables, figures, and plots to get an idea on how to include these in your latex report. 
