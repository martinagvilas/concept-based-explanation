# concept-based explanations for deep neural networks

:warning: WORK IN PROGRESS

This repository provides notebooks with step-by-step tutorials for
implementing concept-based methods for explaining a deep neural networks' internal
representations in human-understandable terms. 

## Methods covered
- [Testing with Concept Activation Vectors (TCAV)](https://arxiv.org/pdf/1711.11279.pdf)
by Kim et al. (2018).
- [Automatic Concept-based Explanation (ACE)](https://arxiv.org/pdf/1902.03129.pdf)
by Ghorbani et al. (2019).
- [Completeness-aware concept-based explanations](https://proceedings.neurips.cc/paper/2020/file/ecb287ff763c169694f682af52c1f309-Paper.pdf) by Yeh et al. (2019)
- [Causal Concept Effect (CaCE)](https://arxiv.org/pdf/1907.07165.pdf)
by Goyal et al. (2020)
- {More to come...}

## Installation
1.  Make a copy of this repository in your local machine.
```bash
git clone https://github.com/martinagvilas/concept-based-explanation.git
cd concept-based-explanation
```

2. Install the required software to run the notebooks. We recommend that you use 
[miniconda](https://docs.conda.io/en/latest/miniconda.html) for the installation:
```bash
conda create --name cbe python=3.8
conda activate cbe
pip install -r requirements.txt
```
