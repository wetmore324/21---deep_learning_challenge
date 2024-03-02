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
  In the initial model 2 hidden layers with RELU activation were selected.  The first layer had 7 nodes while the second layer had 13 nodes.
![image](https://github.com/wetmore324/21-deep_learning_challenge/assets/136288855/6285b0d9-4894-4c78-849c-c108c1d14345)

Were you able to achieve the target model performance?
  The target performance of 75% was not achieved.
![image](https://github.com/wetmore324/21-deep_learning_challenge/assets/136288855/7ad58e68-105e-4754-a7b4-a422e3ae4a0d)

What steps did you take in your attempts to increase model performance? 
  In an attempt to improve the performance more nodes were added as well as a third hidden layer to try to achieve better model performance.
  
Attempt 1 - more nodes adde
![image](https://github.com/wetmore324/21-deep_learning_challenge/assets/136288855/bbc32333-f7f1-4c83-9379-bd677684a427)
![image](https://github.com/wetmore324/21-deep_learning_challenge/assets/136288855/bf3751b2-eafb-48d9-b32e-d45a745b219a)

Attempt 2 - Another increase of nodes
![image](https://github.com/wetmore324/21-deep_learning_challenge/assets/136288855/3f96fa67-f61c-4df1-a43d-af3dc5aac69d)
![image](https://github.com/wetmore324/21-deep_learning_challenge/assets/136288855/61296772-7206-4ebf-a3ce-799f408c8eb4)

Attempt 3 - Added a third layer
![image](https://github.com/wetmore324/21-deep_learning_challenge/assets/136288855/4092663e-d37f-4c59-82df-bcf2b216798b)
![image](https://github.com/wetmore324/21-deep_learning_challenge/assets/136288855/235b6843-ae45-478c-a6b5-068a460d9694)

All of these attempts to improve the test accuracy beyond 75% was not successful.  A different model like Support Vector Machines could be used to produce more accurate results. With this model being linear regression and not producing the accurate results needed we would need to choose a different model and the Support Vector Machine works really well with binary classification data.
