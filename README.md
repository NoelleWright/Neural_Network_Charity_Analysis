# Neural_Network_Charity_Analysis

Purpose:

The purpose of this analysis is to use machine learning to create types of binary classifiers that will determine who will be receiving charotable funds from the Alphabet Soup Organization. There were more than 34,000 organizations that needed to be analyzed to determine if they were successful or not. 

Results:

With data processing, the data was compiled, trained, and evaluated. The three variable components were to determine if the variable was successful. From the dataset, 
The IS_SUCCESFUL column was the target.
The variables that were feature models were every column, except the IS_SUCCESFUL column.
The variables that should be removed are NAMES and EIN due to having no impact on the dataset. 

Compiling, Training, and Evaluating the Models:
1. There were 2 hidden layers in the layers because of a sigmoid output layer. 
2. In order for the model to be reached, the goal needed is 75%, but when the data was ran, it only reached 69% meaning the target model audience was not met. 
3. Steps used to help reach target performance could be resetting the components and trying the models each time without dropping datasets. 


Summary:

The overall results of the deep learning model concluded that after completing the model, the accuracy dropped significantly compared to the inital dataset. This could be due to removing parts of the dataset and not adding more data in place of what was removed. Different machine learning models could be used to help the data reach the initial optimization score. 
