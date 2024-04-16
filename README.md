# Principal Component Analysis (PCA) From Scratch Using Numpy
## Project Overview
This project recreates the PCA algorithm from scratch using numpy for matrix operations. It then compares it to the PCA implementation from scikit-learn. The dataset used is the Iris flower dataset containing sepal length, width and petal length, width for 3 different types of irises' (Setosa, Versicolour, and Virginica) stored in a 150x4. Each type of irises has 50 instances in the dataset. The labels are removed for PCA since the goal is dimensionality reduction.

Recreating the PCA algorithm gives the benefit of

* understanding what happens under the hood of the algorithm
* understanding if the dimension reductionality for a dataset is best achieved using PCA
* understanding the mathematical concepts leveraged by the algorithm
* Allows for model customization

For a detailed explanation on the theory used for this computation, check out the accompanying [article on medium](https://medium.com/@ayoakinkugbe/linear-regression-from-scratch-using-matrices-991df6e28f62)

### Code
You can find the code for this project [here](https://github.com/ayoakin/PCA_from_Scratch/blob/main/Build_PCA_(Principal_Component_Analysis)_from_Scratch.ipynb).

File overview:

* `Build_PCA_(Principal_Component_Analysis)_from_Scratch.ipynb` - the full code from this project


## Environment Setup

### Installation
To follow this project, please install the following locally:

* Python 3.8+
* Python packages
  * pandas
  * numpy
  * scikit-learn

### Data

The data used for this implementation is the salary data originally on [Kaggle](https://www.kaggle.com/datasets/uciml/iris).

You can download the file we'll use in this project here:

* [IRIS.csv](https://github.com/ayoakin/PCA_from_Scratch/blob/main/IRIS.csv) - the Iris dataset used in this project.
