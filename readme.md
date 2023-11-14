# Quantum Machine Learning

by [@alexgcsa](https://twitter.com/alexgcsa) and [@proteinmechanic](https://twitter.com/proteinmechanic)


## Main Colab Notebook
The main material can be accessed via Google Colab Notebook:
- [Understanding Support Vector Classifier (SVC)](https://colab.research.google.com/github/alexgcsa/incob2023/blob/master/SVC.ipynb)





## Extra Colab Notebooks

The extra material can be accessed via Google Colab Notebooks:
- [Classification Colab - Part 1](https://colab.research.google.com/github/alexgcsa/incob2023/blob/master/qmlw_extra_p1.ipynb)
- [Classification Colab - Part 2](https://colab.research.google.com/github/alexgcsa/incob2023/blob/master/qmlw_extra_p2.ipynb)


## Local installation

Alternatively, if you want to run it locally, we suggest you use [Anaconda](https://docs.anaconda.com/free/anaconda/install/) (or [Miniconda](https://docs.conda.io/en/latest/miniconda.html)) to manage a virtual environment and install dependencies.


### First, create an environment with the following command:

```bash
$ conda create -n incob_qml
```

### Then, install dependencies via pip:


```bash
$ conda activate incob_qml

$ conda install python=3.10

$ pip install -r requirements.txt
```

### If you need to run under this environment at any time, use the following command to activate it and open the notebook:

```bash
$ conda activate workshop_ml

$ jupyter lab
```
**OR**
```bash
$ jupyter lab --ip=127.0.0.1 --port=8888
```


