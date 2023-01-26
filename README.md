# Investigating the Intuitive Logic behind Autoregressive Language Models
_Gaia Carenini, Alexandre Duplessis_

This is the code associated to the article [_Investigating the Intuitive Logic behind Autoregressive Language Models_](https://raw.githubusercontent.com/alexandreduplessis/Deep-Learning/main/LLM_Intuitive_Logic.pdf).

### Usage
Just go through the two notebooks in ``/notebooks/`` !

If you want to execute them yourself just pay attention to the fact that the loaded model (GPT2-XL) takes 6GB of memory space.
Google Colab compatible versions of the notebooks will be provided soon...

### Description
This code bases on the code of the article  [_Locating and Editing Factual Associations in GPT_ ](https://github.com/kmeng01/rome).

- In `/notebooks/final.ipynb` we investigate the statistical properties of GPT, and apply the causal tracing technique proposed by K. Meng et al.
- In `/notebooks/editing.ipynb` we apply the editing algorithm ROME of K. Meng et al. for logical relations.

### Requirements
Must be installed
- `torch`
- `numpy`
- `pandas`
- `seaborn`
- `matplotlib`
- `json`

---
_Note:_ This project is part of the Deep Learning course of ENS Ulm (2022-2023).
