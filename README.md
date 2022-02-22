# lsml22
Notebooks for the [2022 course on Large Scale Machine Learning at Mines ParisTech](http://cazencott.info/index.php/pages/LSML-22-Large-Scale-Machine-Learning).

## Day 1: Introduction to large scale ML
* If you are familiar with `scikit-learn` (for example, Mines students who had Data Science in their first year or took "Apprentissage artificiel" previously), work on notebook `1_sklearn_at_scale.ipynb`.
* If you are not familiar with `scikit-learn`, you can start with [this notebook](https://github.com/chagaz/ml-notebooks/tree/master/intro-ml-genetics) to get a hang of things. 

## Day 2: Deep learning
TBA

## Day 3: Stochastic gradient descent
Work on notebook `3_stochastic_gradient_descent.ipynb`.

## Day 4: Deep reinforcement learing
TBA

## Setup
To run the notebooks, you will need Python, [Jupyter](https://jupyter.org/) (either JupyterLab or Jupyter Notebook), and number of Python librairies. The easiest way to install of this is to use [conda](https://docs.conda.io/en/latest/) and set up an environment specific to this course using the file `package_list.yml`. To this end, you can either:
* if you prefer graphical user interfaces: (1) [install Anaconda](https://docs.anaconda.com/anaconda/install/index.html) and (2) follow the instructions under "Importing an environment" [of the tutorial](https://docs.anaconda.com/anaconda/navigator/tutorials/manage-environments/) to import the environment in `package_list.yml`;
* if you prefer the command line: (1) [install conda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html) and (2) use the following instructions in the command line:
```bash
   conda env create -f package_list.yml -n lsml
   conda activate lsml
```


