# Module 21 Challenge Report

## Overview of the Analysis

* The purpose of this challenge is to use deep learning and neural networks to build a model that can create a binary classifier and predict whether applicants will be successful if funded by Alphabet Soup.

* The metadata about each applicant provided by the dataset includes the following:
    * EIN and NAME: Identification columns
    * APPLICATION_TYPE: Alphabet Soup application type
    * AFFILIATION: Affiliated sector of industry
    * CLASSIFICATION: Government organization classification
    * USE_CASE: Use case for funding
    * ORGANIZATION: Organization type
    * STATUS: Active status
    * INCOME_AMT: Income classification
    * SPECIAL_CONSIDERATIONS: Special considerations for application
    * ASK_AMT: Funding amount requested
    * IS_SUCCESSFUL: Denotes if the money used effectively

## Results

### Data Preprocessing
* What variable(s) are the target(s) for your model?
    The target variable used is the "IS_SUCCESSFUL" feature.
* What variable(s) are the features for your model?
    The input variables are all features except "EIN","NAME". 
* What variable(s) should be r
emoved from the input data because they are neither targets nor features?
    "EIN" and "NAME".

#### Compiling, Training, and Evaluating the Model
* How many neurons, layers, and activation functions did you select for your neural network model, and why?
    
    ![Model Hyperparameters](Images/Model_HyperParameters.PNG)

    * From the image above, the model has 80 neurons for the first layer, 30 neurons for the second layer, 2 layers, relu activation fuction for the hidden layers and sigmoid function for the output layer.

* Were you able to achieve the target model performance?
* What steps did you take in your attempts to increase model performance?

3. Summary: Summarize the overall results of the deep learning model. 

4. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.