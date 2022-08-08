# Neural_Network_Charity_Analysis
## Project Overview
  This analyses has been conducted to predict what applications recieved by the foundation will be successful. The model will need to analyze the contents of the foundation and use what it reads to accuratly deem the application a potential success or faliure. the data set we are using to train and test the model contains 34,300 sample applications recieved by the foundation. our goal is to create a model that is at least 75% accurate at predicting application success with this data.
  
  Results
  
    the model
  - The target variable for this model is the IS_SUCCESSFUL Column. the goal of the model is to tell if a application will succeed based on the factors on it.
  
  - The features for this model are as follows: APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL CONSIDERATIONS, and ASK_AMT. all of these columns are factors that may influence whether a project is successful or not
  
  - Since no data is being linked and identifiers are unnecisary for the model the EIN and NAME Column have been removed from the model as extra data.
  
  - for the model 3 hidden layers were used starting at 80 nerons giving approximatly 2 nerons for each of the 43 inputs. from there the nerons were cut in half per layer. relu and sigmoid were used for the functions as they yield the best results for this model.
  
  - the 75% target was not achieved by the model in this current state. more testing is needed to reach the target
  
  - to increase performance, status was removed, a hidden layer was added, the nerons on layer 2 were increased, sigmoind was used on layer 3, and 100 epochs were run.
