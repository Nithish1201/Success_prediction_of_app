# Success Prediction of Mobile Apps in Google Playstore

## Repository Tree

```bash
F:.
├───exp-notebooks
├───google-playstore-apps
├───images
└───notebooks
    └───.ipynb_checkpoints
```

<br/>

# About the Project


Recognising the effort of many aspiring mobile app developer that they have made in making a successful application, we have made this project which predicts the average number of downloads that a app can get when published in Google playstore.

Though google's way of proccessing the payment of any app published in playstore does not completely depend on the number of downloads, but still this feature plays a major role in the success of any developer's application.

The Data for this project was taken from kaggle datasets, which is huge in size when compared to any other tabular data of playstore. Which is going to precursor our success of the project by mitigating the defieciency of data for training.

This project was completly build with python and many important packages of python because, considering the simplicity of both data and model, as of now, we didn't require any deep learning models or faster languages to process.
Every predictions was done with classical machine learning methods.

<br/>

# Structure


- First the data was imported from kaggle using its API and authentication.
- Then the Data has gone through a refined cleaning process.
- Next the cleaned data was taken to have some visualisations and exploratory analysis, by which the data was transformed accordingly .
- Finally the well modified data will go through training with various regression models to find the best fit model.
- Later the finalized model will go through some hyper parameter tuning to reduce its MSE value.

<br/>

 <font size = "3">**NOTE:**</font>

 *All repository directories (```google-playstore-apps``` , ```notebooks``` , ```images```) are auto generative if you execute the notebooks folder in the below mentioned order. 
The directory ```exp-notebooks``` is a folder of experimental notebooks, which is jusat for your reference and will not contribute to the execution of notebooks*

<br/>

# Build With

The below mentioned are some of the most cardinal python modules used in this project

- Numpy 
- Pandas
- Matplotlib
- Seaborn
- sklearn
- Various other packages containing boosting algorithms 

<br/>

# Getting Started


There are certain steps to be followed to have a correct order of proccessing and specific packages to be installed to have a non-disruptive execution.

This guides you to attain the end goal of the project.


**Step-1:**

### Make a python Environment and *activate* them

```
python -m venv venv
source venv/bin/activate
```

**step-2:**

### Clone the repository

```
git clone https://github.com/Nithish1201/Success_prediction_of_app.git
```


 **Step-3:**

### Installing required packages 

```
pip install -r requirments.txt
```

**step-4:**

Get API KEY of Kaggle by logging yourself into the site
<br />

**step-5:**

## Order of Executing the Notebooks

### 1.Playstore-Cleaning.ipynb

    - Cleans the data completely using Pandas.
    - Getting rid of unwanted columns.
    - Handling irrelevent data.
    - Giving features its respective data types.
    - Handling missing values.

**NOTE:**
*Running this notebook completely, will necessarily download a finalised compressed data file of the notebook in your data directory. Later this file is loaded to the following notebook.*

<br/>

### 2.Playstore-Visualization.ipynb

    - Visualizing the data to gain some insights about the data.
    - Giving some graphics to the plots using Matplotlib and seaborn.



**NOTE:**
*Running this notebook completely, will necessarily download some Images which were used later for preparation of final documentation, which will not relate to the processing of further notebooks.*

<br/>

### 3.Playstore-EDA&Responses.ipynb

    - Exploring all the dimensions and structure of the data.
    - Gaining some useful insights like distribution of data and presence of outlier.
    - Handling some categorical features in order to give a good prediction result.



**NOTE:**
*Running this notebook completely, will necessarily download a finalised  compressed data file of the notebook in your data directory. Later this file is loaded to the following notebooks.*

<br/>


### 4.Playstore-RegressionModels.ipynb

    - Various Regression models have been tested to find the best model.
    - Classical machine learning models were not only chose from sklearn but also from other various packages which are aggresive too.


### 5.Playstore-FeatureSelection.ipynb

    - After finalising a best fit model, we gave a try implementing some feature selection models, but unfortunatly they were in vain.


**Warning:**
*Running this notebook completely, with basic system requirements is going to take a long time of processing.*

<br/>


### 6.Playstore-RegressionCatboost.ipynb

    - The finalised model has gone through some manual tuning of hyper parameters and presented as final solution.
    

 *The thoeritical base and better understanging of the project can still be extracted from the final documentation.*

<br/>

# Contributors
   
- Aditi Mittal
- Varun
- Nithish kumar 


 # Contact Info

Name: Nithish kumar\
Github Id: Nithish1201\
Repo Name: Sucess_prediction_of_app\
Email id: nithishnit2002@gmail.com\
Contact: 9360637610