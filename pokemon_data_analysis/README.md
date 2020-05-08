# **Pokemon data analysis**

## Overview

This package provides an implementation of Pokemon data analysis, which is referred from [Michael Metter's kernel](https://www.kaggle.com/mmetter/pokemon-data-analysis-tutorial/notebook). 
I implemented this kernel by using Jupyter notebook, practicing my python skills, and basic data analysis. I found the missing values of the original data, calculate the battel record and winning percentage of the pokemons, and visualize the analysis using Matplotlib and Seaborn just like the original kernal. Moreover, I gave some additional comments for each cells for detailed explanations. 
Finally, I concluded the analysis with linear regression and SVM practice and PCA. 
These techniques could give the prediction and validation process of the analysis. 

This package provides an implementation of Pokemon data analysis, which is orginated from [Michael Metter's kernel](https://www.kaggle.com/mmetter/pokemon-data-analysis-tutorial/notebook). 
The motivation of this project is to understand the basic concept of data analysis including analyze the characteristics of the data set, search for the incomplete part of the data, compensate the dataset with some calculations, and simply visualize our analysis for better understanding. The pokemon dataset could drive an interest to students about the dynamics of the pokemon universe through data and become a great tool to help understanding data analysis. Plus, it might be helpful to practice for python programming skills. 
I tried to follow the process of the notebook of Micheal Metter's kernel, which includes a great job of data analysis with python. I added some additional comments to each cells for detailed explanations of the code.  

The tree structure of this project is given as follows:

``` Unicode
Pokemon_data_analysis
  ├── data
  │    ├── combats.csv
  │    └── pokemon.csv
  └── Pokemon_data_analysis.ipynb: Ipython notebook implementing our project. 
```

### Data description
This dataset is from [Pokemon- Weedle's Cave](https://www.kaggle.com/terminus7/pokemon-challenge) of Kaggle.
- `combats.csv`
- `pokemon.csv`
- `tests.csv`
* Note that: 
    * `pokemon.csv` is the dataset of pokedex.  
    * `combats.csv` is the dataset including battle records of the pokemons.  
    * `tests.csv` is not used for our analysis.

## Install
* Python 3.7
* Numpy
* Matplotlib
* Seaborn
* Pandas

## Contact

- Bumjoon Park (qkrskaqja@snu.ac.kr)

