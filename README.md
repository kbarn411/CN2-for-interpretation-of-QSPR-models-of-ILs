# CN2 for interpretation of QSPR models of ILs

This repo contains codes to reproduce our work on identification of structure-property correlations in ionic liquids using cn2 rule mining algorithm

Corresponding author: Karol Baran (GdańskTech), karol.baran[at]pg.edu.pl

Manuscript status: submitted (2024)

## Project description

Ionic liquids (ILs) have a wide range of applications in various fields, including energy storage, catalysis, and separation processes. Understanding the relationship between IL structure and properties is crucial for optimizing their performance in these applications. In this study, we propose using the CN2 association rule algorithm to analyze the relationship between IL structure and four properties: density, Henry's Law Constant (for IL - CO2 systems), Fractional Free Volume, and toxicity. We used data on a set of ILs from the previous literature findings and represented their molecular structures as molecular fingerprints (MFs). The CN2 algorithm was then used to identify association rules between the structural moieties (in the form of MFs) and the IL properties of interest. The results showed that the algorithm was able to accurately reproduce the findings from previous studies on the relationship between ILs' structure and properties. Furthermore, insights were given into the cation-anion combination boosting properties values based on the association rules identified. This study demonstrates the potential of using the CN2 association rule algorithm with MFs as a tool to ease the interpretation of quantitative structure-property relationship models of ILs. This method can serve as a basis for future studies on the design of novel ILs based on the method's validation performed in this study. 

## Files

- cn2-rule-orange-workflow.ows - main file with workflow proposed in this study
- prepare_dataset.ipynb - auxiliary file to generate molecular fingerprints and prepare datasets for the study