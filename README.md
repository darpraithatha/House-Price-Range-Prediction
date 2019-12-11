# House-Price-Range-Prediction
Predicting the Housing Price Range using the 2017 AHS Data set<br />

# Abtract:
The main goal of this project is to predict the range of selling price of house with a high degree of predictive accuracy using various Machine Learning methods. Given house sale data or explanatory variable such as number of bedrooms, number of bathrooms in unit, housing cost, annual commuting cost etc, the model is built. Next, the model is evaluated with respect to test data, and plot the prediction and coefficients.<br />

# Dataset:
We are using American Housing Survey 2017 data (household.csv in AHS 2017 National PUF v3.0 CSV.zip). Since the dataset is very big, we are just providing the link to our google drive where all relevant project documents are present. The household dataset could not be uploaded in github repo. There is another csv file called AHSDICT_15NOV19_21_17_31_97_S.csv that consist of the mapping information of each feature name to their actual meaning and data type information. This file is already present in github repo. In the AHS microdata, the basic unit is an individual housing unit. Each record shows most of the information associated with a specific housing unit or individual, except for data items that could be used to personally identify that housing unit or individual. The dataset comprises of housing data features like TOTROOMS(Number of rooms in unit), PERPOVLVL(Household income as percent of poverty threshold (rounded)), COMCOST(Total annual commuting cost), JBATHROOMS(Number of bathrooms in unit), UNITSF(Square footage of unit), JGARAGE(Flag indicating unit has a garage or carport), JFIREPLACE(Flag indicating unit has a useable fireplace) etc., and target column as MARKETVAL(Current market value of unit) to evaluate model and also check which amongst all features is the most correlated feature for price prediction.<br />

Two primary datasets used are:<br />
• AHS 2017 Data - provide google drive link<br />
• AHS Codebook Feature Name Mapping - ![Feature Mapping](AHSDICT_15NOV19_21_17_31_97_S.csv)
<br />

# Pre-requisites:
Python 3.7.0<br />
Numpy<br />
Pandas<br />
Scipy<br />
Scikit-learn<br />
Matplotlib<br />
<br />

# Project Implementation:
We defined machine learning models using most of the explanatory variables describing every aspect of residential homes and predict the final price range of each home. 
![Implementation Plan](plan.png)
<br />

# Algorithms Implemented:
In this project, our aim is to implement algorithms which will be able to learn and classify the new observations to correct house price ranges. I decided to use below machine learning algorithms for the same-<br />
• Random Forest (RandomForestClassifier)<br />
• K-Nearest Neighbor (KNeighborsClassifier)<br />
• Decision Tree (DecisionTreeClassifier)<br />
• Multi-layer Perceptron Classifier (MLPClassifier)<br />
• AdaBoost Classifier (AdaBoostClassifier)<br />
• Ensemble Method (Stacking)<br />

# Conclusion:
A range of different models were explored, from relatively simple to more complex ones, with the goal of best predicting home price ranges but also utilizing different data science skills in the process. For this particular problem, the algorithm with best accuracy value is AdaBoost Classifier with test accuracy score of 0.6129 and therefore it can be considered as a good classifier algorithm for house price range prediction problem. Also, the Decision Tree Classifier is close enough with 0.6060 accuracy score. We have tried tuning each algorithm with different hyper-parameter values and finally kept the best results for each. <br />

# Code Execution Details:
For our project, we applied six different machine learning algorithms and using a big dataset (around 161 MB). So, one of the input datasets household.csv could not be uploaded in Github due to size restrictions. All other documents except this dataset, including the source code are uploaded in Github. Also, all the relevant documents presentation slides, project report, source code .ipynb file including the household.csv dataset is present in google drive as well.<br />
Google Drive - https://rb.gy/jdzjde <br />
Github Repo – https://github.com/darpraithatha/House-Price-Range-Prediction<br />
