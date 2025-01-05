# HackathonNAAN

## Description of Project

This project is a Machine Learning Random Forest Regression model created to predict future water quality in local water sources. We took all our data from USGS (United States Geological Survey) of San Joaquin River, which we chose since it was a local area and already has some water quality issues we discovered. We imported it into our database which is made on Google Sheets. Our sheet has 8,000+ lines of data for each parameter. It was coded on Google Colab, which enabled us to create graphs and have a visual way to see our model for users. This design is made for scientists to predict water quality in 1 day, 1 week, and 4 weeks. We were driven to give a short-term and long-term prediction to see how our algorithm would react. By having 4 weeks, we leave time for scientists to apply preventative measures.


## Parameters

Our parameters include Turbidity, Temperature, Dissolved Oxygen, pH, and Specific Conductance. Each of these features affect water quality and the organisms that live there. 

## Google Colab

Our project is split into eight different Google, five including which features are most important in calculating the features (ends with features), two including the predictions' accuracy (Specific_Conductance_Predictions and Turbidity_Predictions), and one with overall prediction's accuracy for all the parameters (Overall_Prediction). To see our code, you can access the desired Google Colab. To see our prediction's accuracy, you can see our graphs in Overall_Prediction, Specific_Conductance_Predictions, and Turbidity_Prediction. 