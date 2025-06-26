# Imperfect Detection in Heterogeneous Complex Ecological Network: A GNN-based Approach
**Official implementation** of the paper:  
👉 [Imperfect Detection in Heterogeneous Complex Ecological Network: A GNN-based Approach](https://dl.acm.org/doi/10.1145/3703323.3703752)  
Published at *CODS-COMAD 2023*

---

## 🔍 Overview

Link prediction is challenging for complex ecological networks as the observed data are often incomplete during field sampling. Given a plant-pollinator network, models using a non-negative matrix factorisation and Poisson N-mixture successfully address the ecological issues with imperfect detection while establishing a binary model for predicting unobserved links. We drive an advanced nonlinear approach using a neural network while exploiting a hybrid strategy of the Poisson N-mixture model and the Gaussian mixture model in statistical ecology. This generates a predictive model for link prediction along with interaction probabilities. Evaluation of our method on test data revealed an AUROC (area under the receiver operating characteristic curve) of 85.4% and AUPRC (area under the precision-recall curve) of 80.1% which is significantly higher compared to the current state-of-the-art solutions. Moreover, it has theoretical support since its optimization technique ensures convergence and scalability.

---

## 🧠 Key Contributions

- Reresentation of ecological networks as heterogeneous graphs.
- GNN based approach to model such complex ecological networks

---

## 📂 Directory Structure

### Plant Pollinator Network 
1. Plant_Pollinator_Data - Cleaned data for the Plant Pollinator network
2. Ecology_GNN_Plant_Pollinator.ipynb - Code for training GNNs Plant Pollinator Network

### Host Parasite Network 
1. Host_Parasite_Data - Cleaned data for the Host Parasite network
2. Ecology_GNN_Host_Parasite.ipynb - Code for training GNns on Host Parasite Network

## Citation
```commandline
@inproceedings{10.1145/3703323.3703752,
author = {Ghosh, Moumita and Sil, Pritam and Dutta, Animesh},
title = {Imperfect Detection in Heterogeneous Complex Ecological Network: A GNN-based Approach},
year = {2025},
isbn = {9798400711244},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3703323.3703752},
doi = {10.1145/3703323.3703752},
booktitle = {Proceedings of the 8th International Conference on Data Science and Management of Data (12th ACM IKDD CODS and 30th COMAD)},
pages = {152–159},
numpages = {8},
keywords = {Link prediction, Statistical ecology, Heterogeneous bipartite graph, Graph neural network, Ecological network},
location = {
},
series = {CODS-COMAD '24}
}
```
