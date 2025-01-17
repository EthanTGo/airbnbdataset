# AirBnb Boston and Seattle dataset

<img src='images/Airbnb.jpg' width=700 height=500>

The following dataset is a combination of two datasets: the AirBnb's Boston dataset and the AirBnb's Seattle dataset. I combined the two dataset in order to gain more insight on different regional comparison on both the Boston and Seattle dataset.


# Motivation

The main motivation behind this project is that it is a start for my Udacity online course. However, I choose to challenge myself by comparing and importing two datasets. This way, I want to try to learn how to make comparisons between the data and see the types of questions I can make from it. 


# File Description

The file structure contains a folder for the datasets and the Jupyter Notebook file. 


# Set Up

Basic data analysis libraries such as numpy, pandas, matplotlib and seaborn was used. Another library that needs to be installed and did not come from the base anaconda environment is missingno. The instructions for installation can be found here: https://anaconda.org/conda-forge/missingno


# Acknowledgements

Both dataset is taken from Kaggle but was ultimately given and provided by Airbnb. A huge thanks for the company to provide the dataset to the public. Here are the links for the datasets:

1. Boston airbnb's dataset: https://www.kaggle.com/airbnb/boston
2. Seattle's airbnb's dataset: https://www.kaggle.com/airbnb/seattle/data

# Results

The results of this project shows an understanding of the dataset and the importance of choosing a model. In the first scenario, I decided to choose a basic linear regression model and had a high mean squared error. But, changing the model from a linear model to a ridge model significantly decrease the mean squared error. These changes combined with hyperparameter optimization may allow for satisfactory predictions to be made on the price of an Airbnb given the chosen variables. 

The data anaysis + visualization enables more understanding of how the variables in the  data is distributed.

Here are some visualizations that enable insights:

<img src='images/price_distribution.png' width=700 height=500>

Here we can see the distribution of the Airbnb price between Boston and Seattle. This gives a good comparison for insights between the two locations.

<img src='images/Boston_Neighborhood.png' width=700 height=500>

This shows the 10 popular neighborhood in Boston

<img src='images/Seattle_Neighborhood.png' width=700 height=500>

This shows the 10 popular neighborhood in Seattle
