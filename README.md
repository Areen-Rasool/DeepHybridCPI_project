
## DeepHybridCPI: A hybrid deep learning framework for compound–protein interaction prediction


### DeepHybridCPI

A hybrid deep learning framework for predicting compound–protein interactions.

Combines:
- Multiscale Graph Neural Network for compound feature extraction
- CNN-LSTM for protein feature extraction 
- Fully connected interaction layers

Goal:
Improve prediction accuracy for  Compound-Protein Interaction.


<div align="center">
<img src="./Figures/a_2.png" width="600">
<br>
</div>


###  Installation & Setup

####  Google Colab (Recommended)

```bash
!pip install torch_geometric
!pip install rdkit
```

#### Train/test DeepHybridCPI:
  
- First, run preprocessing.py using  
  `python preprocessing.py`  

- Second, run train.py using 
  `python train.py --dataset human --save_model` for Human dataset and `python train.py --dataset celegans --save_model` for C.elegans dataset


### Dataset

All data used in this paper are publicly available and can be accessed here: https://github.com/masashitsubaki/CPI_prediction 

###  Citation

If you use DeepHybridCPI in your research, please cite our work:

Rasool, A., Rahman, J. U., & Ali, Q. (2026). DeepHybridCPI: A Hybrid Deep Learning Framework for Compound–Protein Interaction Prediction. Journal of Molecular Graphics and Modelling, 109303.
