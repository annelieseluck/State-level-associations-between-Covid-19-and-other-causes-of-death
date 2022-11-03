The replication material is structured in the following way.

 - data/input: raw mortality and population data.
 - data/output: cleaned data used in the analysis
 - R: R code used to clean the data and perform the analysis
 - figures: contains all figures in the paper
 - tables: contains all tables in the paper

All files in the data/output, figures, and tables folders are produced by the R files starting from the data in the data/input folder.

The `cleanData.Rmd` R Markdown file should be run first as it cleans the raw data and prepares it for the analysis. The `analysis.Rmd` R Markdown file can be run next to produce all the tables and figures in the paper.

