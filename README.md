# Fusemachine-Internship
This repo contains all the documentations prepared, assignments done, and projects covered during my internship at Fusemachines

### Some of the best datasets for practicing your datasciene and pandas skills excluding those cliche datasets like Titanic, Winequality, etc:-
<ul>
  <li>Regression Datasets</li>
  <ol>
    <li><a href='https://www.kaggle.com/shivam2503/diamonds'>Diamond Prices and Carat Regression</a></li>
    <li><a href='https://www.kaggle.com/rodolfomendes/abalone-dataset'>Age of Abalone Shells</a></li>
    <li><a href='https://www.kaggle.com/harlfoxem/housesalesprediction'>King County House Sales</a></li>
    <li><a href='https://data.world/nrippner/ols-regression-challenge'>Cancer Death Rate</a></li>
    <li><a href='https://www.kaggle.com/kumarajarshi/life-expectancy-who/'>Life Expectancy</a></li>
    <li><a href='https://www.kaggle.com/nehalbirla/vehicle-dataset-from-cardekho?ref=hackernoon.com&select=Car+details+v3.csv'>Car Prices</a></li>
  </ol>
  <li>Binary Classification</li>
  <ol>
    <li><a href='https://data.world/exercises/logistic-regression-exercise-1'>NBA rookie stasts</a></li>
    <li><a href='https://www.kaggle.com/fedesoriano/stroke-prediction-dataset'>Stroke Prediction</a></li>
    <li><a href='https://www.kaggle.com/adityakadiwal/water-potability'>Water Potability</a></li>
    <li><a href='https://www.kaggle.com/pcbreviglieri/smart-grid-stability'>Smart Grid Stability</a></li>
    <li><a href='https://www.kaggle.com/pavansubhasht/ibm-hr-analytics-attrition-dataset'>IBM HR analytics & employee attrition</a></li>
    <li><a href='https://www.kaggle.com/uciml/mushroom-classification'>Can I eat this mushroom?</a></li>
    <li><a href='https://www.kaggle.com/ritesaluja/bank-note-authentication-uci-data'>Banknote Authentication</a></li>
    <li><a href='https://www.kaggle.com/wenruliu/adult-income-dataset'>Adult Income Dataset</a></li>
  </ol>
  
  <li>Multi-Class Classification</li>
  <ol>
    <li><a href='https://www.openml.org/d/181'>Yeast Classification</a></li>
    <li><a href='https://www.kaggle.com/nehalbirla/vehicle-dataset-from-cardekho?ref=hackernoon.com&select=Car+details+v3.csv'>Kaggle TPS May 2021</a></li>
    <li><a href='https://www.kaggle.com/c/tabular-playground-series-jun-2021/data?select=train.csv'>Kaggle TPS June 2021</a></li>
  </ol>
  
</ul>

## Chart Suggestion
![image](https://user-images.githubusercontent.com/26330512/149336542-9eeb80a9-24be-4d24-b724-2b05480a6975.png)
![image](https://user-images.githubusercontent.com/26330512/149336627-fd79a7dc-1fe8-47e1-8d92-54d60f349131.png)


## Step by Step Process for Feature Engineering (Convert Raw Data to Useful Data for our machine learning models)
Step 1: 
  - Exploratory Data Analysis
    - As soon as you get the raw data
      - See how many numerical features are there in the dataset {Histogram, Probability Density Function}
      - See how many categorical features are there in the dataset, see how many categories are there in each feature {Boxplot, }
      - Missing Values {Visualize}
      - Outliers {Boxplot}
      - See if the raw data needs cleaning or not
      
Step 2:
  - Handling of the missing values 
    - with mean, median, mode or other imputation techniques
Step 3:
  - Handling imbalanced datasets
    - through upsampling, downsampling or combination of upsampling and downsampling techniques using imbalanced-learn library  
Step 4:
  - Treating the Outliers
Step 5: 
  - Scaling the data 
    - through standardization, normalization or other techniques  
Step 6:
  - Converting the Categorical Features into Numerical Features
    - use labelencoder, onehotencoder, binaryencoder,etc from sklearn or category-encoders 
 
