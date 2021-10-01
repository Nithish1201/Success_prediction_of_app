# Success Prediction of Mobile Apps in Google Playstore

# Description

There are many app developers putting lot of efforts in making and publishing thier apps in google playstore, expecting to get a good revenue out of it. But most of the time they don't get paid as anticipated. This project of predicting the success of an app helps these developers to decide with which factor they should build thier apps and show thier skills on. 

Basically this projects take some inputs from the user like Size, free or Paid, Ad supported or not, Availability of in app purchases or not, no of months from the release date to till date, no of months from last updated to till date etc... After that he will be given the average downloads as the result that he could get with those factors.

This will help a lot of developers create thier apps in a way that could most probably result them with the expected revenue.

<br/>

# About the Project

The data for this project was imported from kaggle datasets. which is huge in size when compared to any other tabular data of playstore. Which is going to precursor our success of the project by mitigating the defieciency of data for training.

This project was developed in python with most common python packages. All the predictions are made using classical machine learning methods.


<br/>


# Repository Tree

```bash
F:.
├───exp-notebooks
├───google-playstore-apps
├───images
└───notebooks
    └───.ipynb_checkpoints
```

<br/>

# Structure


- Importing data from kaggle - using API key and Authentication.
- Data cleaning.
- Visualization and exploratory analysis of cleaned dataset.
- Data transformation based on above mentioned analysis.
- Regression models on transformed data - around 10 regression models to find the best fit model.
- Hyperparameter tuning - to reduce MSE(Mean Squared Error) value of best fit model.

<br/>

 <font size = "3">**NOTE:**</font>

 *The repository directories - ```google-playstore-apps``` and ```images``` are auto generated if ```notebooks``` is executed as mentioned below. 
The directory ```exp-notebooks``` is a folder of experimental notebooks, which is just for reference and will not contribute to the execution of ```notebooks```.*

<br/>

# Built With

The below mentioned are some of the most cardinal python modules used in this project

- Numpy 
- Pandas
- Matplotlib
- Seaborn
- sklearn
- Various other packages containing boosting algorithms 

<br/>

# Getting Started

The below steps are to be executed in the order mentioned for orderly processing and non-disruptive execution.


**Step-1:**

### Create a python Environment and *activate* them.

```
python -m venv venv
source venv/bin/activate
```

**Step-2:**

### Clone the repository.

```
git clone https://github.com/Nithish1201/Success_prediction_of_app.git
```


 **Step-3:**

### Installing required packages -

```
pip install -r requirments.txt
```

**Step-4:**

After logging in to kaggle, obtain the API key and enter when prompted.
<br />

**Step-5:**

## Order of Executing the Notebooks

### 1.Playstore-Cleaning.ipynb

    Data cleaning using Pandas:
        - Getting rid of unwanted columns.
        - Handling irrelevent data.
        - Giving features its respective data types.
        - Handling missing values.

**NOTE:**
*Running this notebook will download a compressed data file in your ```google-playstore-apps``` directory. This file is loaded to the next ```2.Playstore-Visualization.ipynb``` notebook.*

<br/>

### 2.Playstore-Visualization.ipynb

    - Visualizing the data to gain some insights about the data.
    - Styled graphs and charts using Matplotlib and seaborn.


**NOTE:**
*Running this notebook will download images to ```images``` directory (only for reference).*

<br/>

### 3.Playstore-EDA&Responses.ipynb

    - Exploring the dimensions and structure of the data.
    - Gaining useful insights - distribution of data and presence of outlier.
    - Feature scaling.
    - Handling some categorical features for a good prediction result.



**NOTE:**
*Running this notebook will download a compressed data file in your ```google-playstore-apps``` directory. This file is loaded to the next ```4.Playstore-RegressionModels.ipynb``` notebook.*

<br/>


### 4.Playstore-RegressionModels.ipynb

    - Testing various Regression models to find the most accurate model.
    - Classical machine learning models were not only chose from sklearn but also from other various packages which are aggresive too.


**Warning:**
*Running this notebook with basic system requirements may take time for processing.*

<br/>


### 5.Playstore-FeatureSelection.ipynb

    - Feature selection on best fit model, no change in the MSE score.


**Warning:**
*Running this notebook with basic system requirements may take time for processing.*

<br/>


### 6.Playstore-RegressionCatboost.ipynb

    - Manual hyperparameter tuning on final model.

    
**Warning:**
*Running this notebook with basic system requirements may take time for processing.*

<br/>
    
**Note:**
 *The thoeritical base and better understanging of the project can still be extracted from the final documentation.*

**Note:**
 *The notebooks ```4``` and ```5``` are optional.*


<br/>

# Contributors
   
- Aditi Mittal
- Nithish kumar 
- Varun


 # Contact Info

Name: Nithish kumar\
Github ID: Nithish1201\
Repository Name: Sucess_prediction_of_app\
Email ID: nithishnit2002@gmail.com\
Contact: +91 9360637610