# Yelp
Analyzing 10Gb of Yelp Reviews Data
# Analyzing 10Gb of Yelp Reviews Data

For this project, I set up a Spark Cluster on AWS EMR for loading and running some analysis on Yelp’s Reviews and Businesses dataset (about 10gb) from Kaggle. I will run my analysis via Jupyter Notebook with PySpark in performing basic data analysis tasks on information sources that are too large to manage in memory.

## Part I: Installation and Initial Setup

In this portion, I import the necessary dependencies and load the dataset as a pyspark dataframe.

## Part II:  Analyzing Categories

For this part, I take a stab at denormalizing the categories that are associated with each business (there may be more than one, presented as a string of comma separated identifiers) and then running some basic analysis on the result.

## Part III: Do Yelp Reviews Skew Negative?

For this next part, I attempt to answer the question: are the (written) reviews generally more pessimistic or more optimistic as compared to the overall business rating. Review data is used in this session.

## Part IV: Should the Elite be Trusted? 

For this final part,I try to answer the question: how accurate or close are the ratings of an "elite" user (check Users table schema) vs the actual business rating. User data is used in this session. 

# File structure 

project02/

+-- Analysis.ipynb

+-- Analysis.pdf

+-- assets/

+-- +-- cluster_configuration.png

+-- +-- notebook_configuration.png

+-- README.md


## Files

Analysis.ipynb contains my analysis and the outputs of the code. 

Analysis.pdf is the pdf version of Analysis.ipynb. 

cluster_configuration.png is a screenshot of the running cluster. 

notebook_configuration.png is a screenshot of the running notebook.

README contains a brief blurb describing the project and the technology leveraged to conduct analysis. It is written in jupyter notebook. 

## cluster configuration 





## notebook configuration

![notebook](/Users/apple/Desktop/project02/assets/notebook_configuration.png)
