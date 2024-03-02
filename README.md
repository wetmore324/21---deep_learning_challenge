# Alphabet Soup Report Analysis

## Overview of the Analysis

In the challenge a tool was developed to allow Alphabet Soup to select applicants for funding with the best chances of success in their ventures.  From Alphabet Soup's business team, a CSV containing more than 34,000 organizations was received.  This dataset allowed the creation of a neural network model.  This binary classifier can predict whether applicants will be successful if funded by Alphabet Soup.

## Data Preprocessing

What variable(s) are the targets for your model?
  Variable used for target is the column "IS_SUCCESSFUL"

What variable(s) are the features for your model?
  Variables used for the features are all other columns except "EIN", "NAME" and "IS_SUCCESSFUL".

What variable(s) should be removed from the input data because they are neither targets nor features?
  These variables removed are "EIN" and "NAME".

![image](https://github.com/wetmore324/21-deep_learning_challenge/assets/136288855/c0489e42-9a1d-464e-b16c-655201855a88)

## Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?

Were you able to achieve the target model performance?

What steps did you take in your attempts to increase model performance? 
  In an attempt to improve the performance a third hidden layer was added to the model to try to achieve more accurate results.
