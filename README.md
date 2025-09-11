# What is Protein Cleaver

Protein Cleaver is a web-based tool designed to systematically evaluate protein regions based on their likelihood of identification. It offers users rich annotation and visualization capabilities for both sequence and structural data.

# How to Run Protein Cleaver

Protein Cleaver is built using R Shiny and is compatible with any system that has R installed. To launch Protein Cleaver, simply enter the following commands in the R console:

```r
install.packages('shiny')
library(shiny)
shiny::runGitHub('ProteinCleaver', 'gkoulouras', ref="main")


