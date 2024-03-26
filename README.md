# F1 Points Prediction Project 🏎️ 

## Links to documents
* [Data Collection Python Files](https://github.com/nat13lla/Capstone/tree/main/datacollection)
  * [Combining all dataframes](https://github.com/nat13lla/Capstone/blob/main/datacollection/Capstone_combining_dataframes.ipynb)

* [Data Maniulation Python Files](https://github.com/nat13lla/Capstone/tree/main/datamanipulation): 
  * [Data Cleaning](https://github.com/nat13lla/Capstone/blob/main/datamanipulation/Data_Cleaning.ipynb), [EDA](https://github.com/nat13lla/Capstone/blob/main/datamanipulation/EDA.ipynb) , [Train/Test/FE/ML/Interface](https://github.com/nat13lla/Capstone/blob/main/datamanipulation/TrainTest_Split_FE.ipynb)

* [Data CSV Files](https://github.com/nat13lla/Capstone/tree/main/data_files)
  * [Final CSV](https://github.com/nat13lla/Capstone/blob/main/data_files/ordered_data.csv)


## Project Aim:
The objective of this project is to create a model that can be used to predict whether an f1 driver will achieve points at a particular race, using their starting position and other relevant variables. The user should be able to choose the driver and the circuit and input a starting position, for the model to predict whether that driver could reach the top 10 to achieve points in that race. The function would use a logistic regression model to predict the outcome. I have a keen interest in Formula 1 and I believe it would be fascinating to explore past data to analyze the relationship between qualifying results/ starting positions and race outcomes.


## Data Collections : Ergast
I gathered relevant F1 data from the Data repository API, which contains comprehensive historical data on Formula One. I combined several datasets, including [Race Results](http://ergast.com/mrd/methods/results/) , [Driver Information](http://ergast.com/mrd/methods/drivers/) , [Constructor Information](http://ergast.com/mrd/methods/constructors/) , [Circuit Information](http://ergast.com/mrd/methods/circuits/) and more.

