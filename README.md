[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/27410/27410-2020-group-project-group-14-vitamin-d-production/main)

# 27410 - Group assignment - Group 14 - [D-vitamin production through Saccharomyces cerevisiae]

## Project summary

The aim of this project is to simulate vitamin D production in yeast (Saccharomyces cerevisiaea), as well as optimise the reaction in various ways such as optGene, and FSEOF. Furthermore, manual knockouts have been utilised to attempt optimization. The pathway used is from a research paper, using zymosterol (a native metabolite) as precursor to produce 7-Dehydrocholesterol, which is a precursor to vitamin D. This is done through three reactions, with a final concentration reached of 0.041 mmol gDW^-1 h^-1. The optimization analyses used did not lead to any useful optimization method.

## Project overview
Describe how your project is organized ...
This project is organized with the text of the report being presented in the file [Report.ipynb](Report.ipynb) and the code for the results presented are located in different files across the repository.
The project code is meant to be read in the following order:

0. [0-Code_Memote.ipynb](0-Code_Memote.ipynb) - this document covers the memote analyses of four different yeast models.

1. [1-Code_Heterologous-pathway.ipynb](1-Code_Heterologous-pathway.ipynb) - this document covers the model and addition of the heterologous reactions.

2. [2-Code_Carbon-sources.ipynb](2-Code_Carbon-sources.ipynb) - this document covers analysis of what carbon source may be most efficient.

3. [3-Code_PPP.ipynb](3-Code_PPP.ipynb) - this document covers the phenotypic phase plan analysis of manual knock-outs.

4. [4-Code_Automatic-optimization.ipynb](4-Code_Automatic-optimization.ipynb) - This document covers automatic optimization attempts such as optGene

5. [5-Code_FSEOF.ipynb](5-Code_FSEOF.ipynb) - This document covers FSEOF analysis of the model

6. [6-Code_Co-factor.ipynb](6-Code_Co-factor.ipynb) - This document covers cofactor-swapping optimization analysis

The metabolic models that are used are located in the "data" folder and the figures are located in the "figures" folder.


