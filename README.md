# F1 Points Prediction Project 🏎️ 

## Links to documents
* [Data Collection Python Files](https://github.com/nat13lla/Capstone/tree/main/datacollection)
  * [Combining all dataframes](https://github.com/nat13lla/Capstone/blob/main/datacollection/Capstone_combining_dataframes.ipynb)

* [Data CSV Files](https://github.com/nat13lla/Capstone/tree/main/data_files)
  * [Final CSV](https://github.com/nat13lla/Capstone/blob/main/data_files/ordered_data.csv)

* [Data Maniulation Python Files](https://github.com/nat13lla/Capstone/tree/main/datamanipulation): 
  * [Data Cleaning](https://github.com/nat13lla/Capstone/blob/main/datamanipulation/Data_Cleaning.ipynb), [EDA](https://github.com/nat13lla/Capstone/blob/main/datamanipulation/EDA.ipynb) , [Train/Test/FE/ML](https://github.com/nat13lla/Capstone/blob/main/datamanipulation/TT_FE_ML.ipynb)

* [User Interface](https://github.com/nat13lla/Capstone/blob/main/Userinterface/Interface.ipynb)
  * [Pickle file](https://github.com/nat13lla/Capstone/blob/main/Userinterface/logregmodel.sav)


## Project Aim:
The objective of this project is to create a model that can be used to predict whether an f1 driver will achieve points at a particular race, using their starting position and other relevant variables. The user should be able to choose the driver and the circuit and input a starting position, for the model to predict whether that driver could reach the top 10 to achieve points in that race. The function would use a logistic regression model to predict the outcome. I have a keen interest in Formula 1 and I believe it would be fascinating to explore past data to analyze the relationship between qualifying results/ starting positions and race outcomes.


## Data Collections : [Ergast](http://ergast.com/mrd/)
I gathered relevant F1 data from the Data repository API, which contains comprehensive historical data on Formula One. I combined several datasets, including [Race Results](http://ergast.com/mrd/methods/results/) , [Driver Information](http://ergast.com/mrd/methods/drivers/) , [Constructor Information](http://ergast.com/mrd/methods/constructors/) , [Circuit Information](http://ergast.com/mrd/methods/circuits/) and more.



## EDA
Exploratory data analysis allowed us to gain insights into circuit analysis, driver nationality, championship wins, and other key factors influencing driver and constructor performance. This analysis was crucial in understanding the sport and informing our modeling approach


## Machine Learning Models:
The main metric I plan on using is accuracy, aiming to achieve a consistent level across both the test data and the train data. The [example model]( https://f1-predictor.gjd.one/) claimed to have base initial accuracy of between 0.50 and 0.68, across all models so I am aiming for a final accuracy of around 0.75 or higher to create a usable and functional model using Logistic Regression.


## Developed by:
- Natalie Coyle
  - GitHub : https://github.com/nat13lla
  - Linked in: https://www.linkedin.com/in/natalie-coyle-b4b437168/

## Keywords:
Formula One (F1), Motorsports, Points Prediction, Model Creation, Logistic Regression, Data Collection, Ergast API, Data Manipulation, Data Cleaning, Exploratory Data Analysis (EDA), Feature Engineering (FE), Train/Test Split, Machine Learning (ML), Interface Development, Predictive Modeling, Circuit Analysis, Driver Performance, Constructor Performance, Qualifying Results, Race Outcomes, User Input, Accuracy, Historical Data, Championship Wins, Data Repository, User Interface, Test Data, Training Data, Relevant Variables, Starting Position, Top 10 Finish, Points Prediction, Formula One Data, Comprehensive Data, Example Model Benchmark, Usable Model, Functional Model, Performance Metric, Data Analysis, Model Evaluation
