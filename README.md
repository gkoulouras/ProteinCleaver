# What is Protein Cleaver

Protein Cleaver is a web-based application that systematically assesses regions of proteins that are likely or unlikely to be identified. It provides users with extensive sequence and structure annotation and visualization features.

# How to Run Protein Cleaver

Protein Cleaver is developed in R Shiny and can be run on any platform with R installed. To execute Protein Cleaver, use the following commands in the R console:

```r
install.packages('shiny')
library(shiny)
shiny::runGitHub('ProteinCleaver', 'gkoulouras', ref="main")


