# EECS-731---Fall-2020---Assignment-5---Forecast-Order-Demand-and-Visualization

Project 5 - Product Demand
The dataset contains historical product demand for a manufacturing company with footprints globally. The company provides thousands of products within dozens of product categories. There are four central warehouses to ship products within the region it is responsible for. Since the products are manufactured in different locations all over the world, it normally takes more than one month to ship products via ocean to different central warehouses. If forecasts for each product in different central with reasonable accuracy for the monthly demand for month after next can be achieved, it would be beneficial to the company in multiple ways.

The overall goal is to build one or more forecasting models to determine the demand for a particular product using the other columns as features.

The dataset can be found at: https://www.kaggle.com/felixzhao/productdemandforecasting  (File size is too big to upload)

Structure/steps:

A deatiled explanantion at each step is mentioned as we walk down the code and results in the jupyter notebook (uploaded on GitHub).

Steps (Data processing and evalaution) :

Imported required modules

Read the data csv file
Initial data analysis and cleaning (checking for null values)
Filter the column data based on the requirements that will help to provide visual representations

Data prepration
  Product with maximum demand
  Remove outliers
  Traina and test data
  
  Ananlysis
  ARIMA
  Simple smoothing
  Exponenetial smoothing
  Decomposition
  
  
 Summary: We showed that it is possible, with trivial models, to lower the mean average forecasting error to only around 20% in terms of volume of command. This should prove that there is a predicting potential in this dataset that only waits to be exploited.
