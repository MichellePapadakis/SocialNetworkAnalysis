
# Overview

This repository contains the final document (`.pdf`) of the social network analysis for one New Jersey middle school, including figures, data summaries, and modeling results.

The dataset is associated with the paper:
> **Paluck, E. L., Shepherd, H., & Aronow, P. M. (2016).**  
> *Changing climates of conflict: A social network experiment in 56 schools.*  
> *Proceedings of the National Academy of Sciences, 113*(3), 566–571.  
> [https://doi.org/10.1073/pnas.1514483113](https://doi.org/10.1073/pnas.1514483113)

The anonymized data are openly shared via the [Inter-university Consortium for Political and Social Research (ICPSR, Study 370)](https://www.icpsr.umich.edu/web/civicleads/studies/37070). For additional details about the study design, data collection, and analysis methods, please refer to the original publication.

## Summary of Activities

In this analysis, we:
- **Examined Network Structure**: Calculated global metrics (e.g., density, average degree, average path length, transitivity, and reciprocity).  
- **Compared with Random Baselines**: Selected a suitable random network model, highlighting how the empirical networks deviate from random structures.  
- **Explored Centralities**: Investigated in-degree and other centrality measures (e.g., betweenness, eigenvector) to identify “influential” students and track their positions over time.  
- **Analyzed Demographic Factors**: Assessed how variables such as gender, grade, and age interact with social and conflict ties.  
- **Community Detection**: Used a leading eigenvector algorithm to detect clusters, examining how these align with demographic attributes.  
- **Fitted an ERGM**: Applied an exponential random graph model to explore how demographic and network factors predict the formation of ties.

Please consult the attached `.pdf` for the full set of figures, detailed findings, and modeling results.
