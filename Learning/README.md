# STEPS
- activate anaconda                (~/anaconda)
- create enviroment                (ML-finance)
- activate that enviroment         (ML-finance)
- install anaconda dependencies    (conda)
- install pip dependencies         (pip)
- fetch data                       (requests)
- ...                              (...)
- ...                              (...)
- ...                              (...)
- ...                              (...)




#### Anaconda on linux 
- make sure to go into /anaconda dir inside of /root
    - Activate the venv
        - source ~/anaconda3/bin/activate



#### Create Anaconda Enviroment
- conda create -n ENV_NAME python=PYTHON_VERSION
    - ex: conda create -n ML-finance python=3.9




#### Activate Anaconda Enviroment
- conda activate ENV_NAME




#### Activate Jupyter Notebook
- jupyter notebook --allow-root



#### FETCHING DATA SOURCES
- Crypto Wizards
- Financal Model Prep
- Quandl







#### PYTHON LIST vs. NUMPY ARRAY vs. PYTORCH TENSOR
- Lists: regular serialized python collection datasets
    - Most common data structure in python

- Numpy Arrays: Low latency mutable collections
    - Common with calculative applications that rely on effeciant number crunching

- Pytorch Tensors: Collections that can utilize the GPU and the TPU
    - utilized with machine learning | Neural Networks






## Class Inheritance
- nn.Module
    - Neural Network Class interface that will extend the functionality of class objects that we define
        - ex: Class StockTrader(nn.Module)

