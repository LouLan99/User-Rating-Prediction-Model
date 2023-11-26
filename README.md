[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/0GBBWOiF)
## Google play store rating predictions for applications
=========================

  Introduce your target variable, and which types of information you will use to predict it. Highlight the key stages of data manipulation and the different models you explore. Also fill in the relevant sections of the 'Project Organisation' header with the names of data files and notebooks. Remove the unused sections.

### Project Overview
Google play store was launch in August 2008, It was at first known as Android Market then renamed in 2012 by its current name. Google play store has been growing since and now contain to this day more than 3 million applications including more than 4 hundred thousand games. Google play store make 54 billions in revenue. 

Google has the opportunity to recommand new high quality application to attract customer attention to google play store. The developpers will be able to see what application is popular or not and create new application based on the feature of the other existing application and possibbly improve some applications. Sellers will be able to sell new applications, increase sells and also apply some e-shops within an application.

### Problem Statement
How might we use machine learning to predict the user rating with the help of
other features of an App.

### Data Description:
Our Data set contain 2312944 rows and 24 columns, we decided to work on a extract with 10000 rows for our  
Our target variable is Rating columns which is the average rating of an application. 
Our problem is a Supervise learning regression problem. To solve this problem we will use a Linear Regression Model and Decision Tree Regressor. 

### Project Flowchart



### Project Organization

* `data` 
https://drive.google.com/file/d/1lcg1z_k0_AlNGR7a8truXsLHSuL2Bd2Q/view?usp=drive_link 

* `notebooks`
01-data-loading-cleaning.ipynb : This notebook is for loading our dataset and cleaning it from duplicated and missing data. 

02-eda.ipynb : This notebook is for analyse our columns seperatly at first and then see if our columns are corelated with our target variable.

03-pre-processing.ipynb : This notebook is for transforming our categorical columns into numerical columns throught various technique such as creating filter, doing dummies and changed datatypes.

04-modelling baseline model.ipynb : This notebook 

05-modelling Linear regression with pipeline and gridsearch.ipynb : 

06-modelling Decision Tree Regressor with pipeline, gridsearch.ipynb : 

07-findings.ipynb :

* `src`
    - Contains the project source code (refactored from the notebooks)

* `.gitignore`
    - Part of Git, includes files and folders to be ignored by Git version control

* `capstine_env.yml`
    - Conda environment specification

* `Makefile`
    - Automation script for the project

* `README.md`
    - Project landing page (this page)

* `LICENSE`
    - Project license

### Dataset

...
...
...

### Credits & References

...
...
...

--------