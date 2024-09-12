# Deep Learning Challenge Analysis

* Overview - The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. I will create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.
  
# Data Preprocessing 
* What variable(s) are the target(s) for your model? The target for each model was the IS_SUCCESSFUL column. The goal is to predict which applicants will be succussful.
* What variable(s) are the features for your model? The features for the model are the remaining columns except EIN and NAME. Those columns include APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT.
* What variable(s) should be removed from the input data because they are neither targets nor features? In the first model I removed the EIN and NAMES. For the second model, I removed EIN, STATUS, and SPECIAL_CONSIDERATION.

# Compiling, Training, and Evaluating the Model
* How many neurons, layers, and activation functions did you select for your neural network model, and why? In the first model, I used two hidden layers. The first had 80 neurons and the second had 30. In the second model, I used three hidden layers where the first had 100 neurons, the second 30 and the third 10. For both models, sigmoid activation was the output layer used. 
* Were you able to achieve the target model performance? In the first model, accuracy was only 73%. By making some adjustments in the second model, accuracy increased to 79%.
* What steps did you take in your attempts to increase model performance? To increase model performance, I dropped more columns and used an addiional hidden layer. 
