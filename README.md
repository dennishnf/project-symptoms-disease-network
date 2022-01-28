[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.png)](https://www.python.org/)
[![MIT Licence](https://img.shields.io/badge/License-MIT-blue.png)](https://opensource.org/licenses/mit-license.php)
[![Ask Me Anything !](https://img.shields.io/badge/Ask%20me-anything-1abc9c.png)](https://github.com/dennishnf/project-symptoms-disease-network/issues)
[![Open Source Love](https://img.shields.io/badge/Open%20Source-%E2%9D%A4-1abc9c.png)](https://github.com/dennishnf/project-symptoms-disease-network/)
[![Tweet](https://img.shields.io/twitter/url/http/shields.io.svg?style=social)](https://twitter.com/intent/tweet?text=Download%20and%20use%20the%20Project:%20Symptoms-Disease%20Network&url=https://github.com/dennishnf/project-symptoms-disease-network&hashtags=network,symptoms,disease,networkx)    


# Project Symptoms-Disease Network

## Overview

Analysis of the Symptoms-Disease Network database using communities.



## Approach

The steps developed in this project were as follows:

<p align="center">
<img src=".images-readme/approach.png" alt="figure" width="700"/>
</p>


## Dataset

The dataset was extracted from the paper: "Human symptoms–disease network" [Link](https://www.nature.com/articles/ncomms5212).

More exactly, here we employ the "Supplementary Data 3": Term co-occurrences between symptoms and diseases measured by TF-IDF weighted values. This table includes 147,978 records of symptom and disease relationships. 

<p align="center">
<img src=".images-readme/dataset_table.png" alt="figure" width="500"/>
</p>


## All Networks: bipartite graph and their projections

<p align="center">
<img src=".images-readme/networks_all.png" alt="figure" width="800"/>
</p>


## Communities of Diseases Network using Louvain

<p align="center">
<img src=".images-readme/communities_diseases.png" alt="figure" width="800"/>
</p>


## Bipartite graphs of each community by symptoms and diseases 

<p align="center">
<img src=".images-readme/analyzing_communities_1.png" alt="figure" width="700"/>
</p>

<p align="center">
<img src=".images-readme/analyzing_communities_2.png" alt="figure" width="700"/>
</p>



## Table of the characterization of each community by symptoms

<p align="center">
<img src=".images-readme/table_symptom_disease.png" alt="figure" width="450"/>
</p>


## Predict the disease category based on symptoms

<p align="center">
<img src=".images-readme/prediction_results.png" alt="figure" width="800"/>
</p>


## References

- Zhou, X., Menche, J., Barabási, AL. et al. Human symptoms–disease network. Nat Commun 5, 4212 (2014). [https://doi.org/10.1038/ncomms5212](https://doi.org/10.1038/ncomms5212)    



<!---

git pull
git add -A
git commit -m "updating readme"
git push -u origin main

--->


