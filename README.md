
# 🧬 DeepHybridCPI: A hybrid deep learning framework for compound–protein interaction prediction

## 📌 Overview

**DeepHybridCPI** is a hybrid deep learning framework for predicting compound–protein interactions (CPI). It combines:

- **Multiscale Graph Neural Network** for compound feature extraction
- **CNN–LSTM architecture** for protein feature extraction
- **MLP module** for integrating compound and protein embeddings

### 🎯 Goal:
Improve accuracy and robustness of CPI prediction


<div align="center">
<img src="./Figures/a_2.png" width="600">
<br>
</div>


## ⚙️ Installation & Setup

###  💻 Google Colab (Recommended)

```bash
!pip install torch_geometric
!pip install rdkit
```

### Train/test DeepHybridCPI:
  
- First, run preprocessing.py using
```bash
  `python preprocessing.py`  
```

- Second, run `train.py`:

 🧍 For Human dataset:
  ```bash
  python train.py --dataset human --save_model
  ```

 🐛 For C. elegans dataset:
  ```bash
  python train.py --dataset celegans --save_model
  ```

## 📊 Datasets

- 🌐 Public dataset used in this work: https://github.com/masashitsubaki/CPI_prediction 


## 📄 Published Paper

<p align="center">
  <a href="https://github.com/Areen-Rasool/DeepHybridCPI_project/raw/main/paper/DeepHybridCPI_paper.pdf" target="_blank">
    <img src="https://img.shields.io/badge/Download%20Paper-DeepHybridCPI-blue?style=for-the-badge&logo=googledrive">
  </a>
</p>

📚**Citation:**  
Rasool, A., Rahman, J. U., & Ali, Q. (2026). DeepHybridCPI: A Hybrid Deep Learning Framework for Compound–Protein Interaction Prediction. *Journal of Molecular Graphics and Modelling*, 109303.
