# What is Protein Cleaver

Protein Cleaver is a web‑based tool designed to systematically evaluate protein regions based on their likelihood of identification. It offers rich annotation and visualization capabilities for both sequence and structural data, enabling researchers to explore digestion‑derived peptides in an intuitive and interactive environment.

# How to Run Protein Cleaver

Protein Cleaver is built using **R Shiny** and is compatible with any system that has R installed. To launch Protein Cleaver, run the following commands in your R console:

```r
install.packages('shiny')
library(shiny)
shiny::runGitHub('ProteinCleaver', 'gkoulouras', ref="main")
```

# Publication

Protein Cleaver is described in detail in the following peer‑reviewed article:
**https://www.frontiersin.org/journals/bioinformatics/articles/10.3389/fbinf.2025.1576317/full**

# How to Cite

If you use Protein Cleaver in your research, please cite:

**Koulouras G, Xu Y. Protein cleaver: an interactive web interface for in silico prediction and systematic annotation of protein digestion-derived peptides. *Front Bioinform.* 2025 Sep 4;5:1576317. doi: 10.3389/fbinf.2025.1576317. PMID: 40980690; PMCID: PMC12445168.**

# Contact

For questions, suggestions, or general feedback, please email:

**gkoulouras {at symbol} gmail {dot symbol} com**

To report a bug, I encourage you to open an issue on GitHub so the discussion is visible to everyone.
