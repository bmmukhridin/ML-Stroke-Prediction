# ML-Stroke-Prediction
### Analysis and Model Prediction on Healthcare Dataset with Stroke

Author: Mukhriddin Bakhramov

Business Problem:

Determine whether a Health Insurance client should pay a Premium for being high-rish of stroke and Increase Company's profit margin by reducing unexpected insurance claims and improving risk-analysis per client.

### Methods
* remove all duplicates to avoid repeating data
* correct all data inconsistencies (mislabled, unnecessary extra character)
* Impute missing values to keep data integrity and avoid model prediction errors

### Exploratory Data Analysis
![image](https://github.com/bmmukhridin/project-2-part-1/assets/73002669/7a648fa3-1c9d-45aa-a362-ae9132221f39)
Here we can see that the majority in this dataset are Female and we have broad range of age but most common are ages early-mid 40s and 80s


![image](https://github.com/bmmukhridin/project-2-part-1/assets/73002669/11273c61-4997-4b7a-b0f8-b7addb05830a)
This Graph represents the occurrences of stroke and their current health conditions, Location, and if they have bad smoking habbits

![image](https://github.com/bmmukhridin/project-2-part-1/assets/73002669/fd5344af-88f2-47b9-8092-454ac951b02e)
From chart above we can see BMI increases by AGE!

### Models

* RandomForest - is an ensemble learning method for classification, regression and other tasks that operates by constructing a multitude of decision trees at training time

* LinearRegression - Linear regression is a type of statistical analysis used to predict the relationship between two variables.

##### Recommendations:

* more data means more opportunity to find commonality for analysis and paterns for model predictions, we can't go wrong with adding more data in our dataset
* gather more relavant data with higher concentration of clients with history of stroke so that our model can generalize and better learn the patterns from clients with actual stroke history

##### Limitations & Next Steps:

* the use of imblance dataset in machine learning model limits our capability to fine-tune our models to better understand patterns in our dataset
* next Step - Explore better techniques on handling imblance dataset.
