<h1 align="center">Predict chance of success  ventures </h1>
<h3 align="center">Alphabet Soup Charity</h3>
<h3 align="center">Deep Learning Model</h3>
<div align="center">
	<img src="images/log.png">
</div>

## Overview
This project is focused on developing a deep learning model to assist the nonprofit organization Alphabet Soup in selecting funding applicants who have the highest likelihood of success. Using historical data, we aim to build a binary classifier that predicts the success of applicants based on various features.

## Data Preprocessing
- Target Variable: 
IS_SUCCESSFUL - This column indicates whether an applicant was successful.
- Feature Variables:
APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS,ASK_AMT 
- Removed Variables:
The EIN and NAME columns were removed because they are identification variables and do not contribute to the predictive analysis.
Compiling, Training, and Evaluating the Model

## Model Architecture:

### Initial Model
<div align="left">
	<img src="images/InitialModelParam.png">
</div>
### Model Performance:
- Number of epochs=100
<div align="left">
	<img src="images/InitialModelAccuracy.png">
</div>

Initial accuracy achieved was approximately 72.54%, which did not meet the target accuracy of 75%.

## Feature Engineering: 
Tested different feature engineering techniques, such as binning rare categorical variables.
## Model Tuning:
Adjusted the number of neurons and layers, and experimented with different activation functions and the number of epochs.


## Optimizations Model Architecture:

### First optimization Attempt 
<div align="left">
	<img src="images/InitialModelParam.png">
</div>
#### Model Performance:
- Number of epochs=100
<div align="left">
	<img src="images/InitialModelAccuracy.png">
</div>

### Second Optimization Attempt
<div align="left">
	<img src="images/InitialModelParam.png">
</div>
#### Model Performance:
- Number of epochs=100
<div align="left">
	<img src="images/InitialModelAccuracy.png">
</div>
### Thrid Optimization Attempt
<div align="left">
	<img src="images/InitialModelParam.png">
</div>
#### Model Performance:
- Number of epochs=100
<div align="left">
	<img src="images/InitialModelAccuracy.png">
</div>src="images/classificationreport.png">
</div>

## Summary
The deep learning model demonstrated an accuracy of 72.54%, slightly below the target of 75%. 
While the model showed potential, further optimization and feature engineering are necessary.

## Recommendation for Alternative Model
Considering the complexity and nature of the data, 
a Random Forest classifier could be an alternative model to explore. Random Forests are robust to over fitting and can handle a large number of input features, potentially improving accuracy.