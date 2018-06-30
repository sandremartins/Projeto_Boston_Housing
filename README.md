Project 1: Model Evaluation & Validation
Neste projeto, vamos avaliar o desempenho e o poder de estimativa de um modelo que foi treinado e testado em dados coletados dos imóveis dos subúrbios de Boston, Massachusetts. Um modelo preparado para esses dados e visto como bem ajustado pode ser então utilizado para certas estimativas sobre um imóvel – em particular, seu valor monetário. Esse modelo seria de grande valor para alguém como um agente mobiliário, que poderia fazer uso dessas informações diariamente.

## Predicting Boston Housing Prices

### Install

This project requires **Python 2.7** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html)

Udacity recommends our students install [Anaconda](https://www.continuum.io/downloads), a pre-packaged Python distribution that contains all of the necessary libraries and software for this project. 

### Code

Template code is provided in the `boston_housing.ipynb` notebook file. You will also be required to use the included `visuals.py` Python file and the `housing.csv` dataset file to complete your work. While some code has already been implemented to get you started, you will need to implement additional functionality when requested to successfully complete the project.

### Run

In a terminal or command window, navigate to the top-level project directory `boston_housing/` (that contains this README) and run one of the following commands:

```ipython notebook boston_housing.ipynb```  
```jupyter notebook boston_housing.ipynb```

This will open the iPython Notebook software and project file in your browser.

### Data

The dataset used in this project is included with the scikit-learn library ([`sklearn.datasets.load_boston`](http://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_boston.html#sklearn.datasets.load_boston)). You do not have to download it separately. You can find more information on this dataset from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Housing) page.
