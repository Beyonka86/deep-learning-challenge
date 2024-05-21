1. Overview of the analysis: The purpose of this analysis is the nonprofit foundation Alphabet Soup finds a tool that can help in selecting applicants for funding with the best chance of success in their venture. Using machine learning and neural networks, we can use features within the dataset to predict whether the applicants will be successful if they are funded by Alphabet Soup foundation. 

2. Results: Using bulleted lists and images to support your answers, address the following questions:
•	Data Preprocessing
o	What variable(s) are the target(s) for your model?
The target variable “y” is the “IS_SUCCESSFUL” column.
o	What variable(s) are the features for your model?
The features of the model “X” are "IS_SUCCESSFUL" column as: "APPLICATION_TYPE" , "AFFILIATION", "CLASSIFICATION", "USE_CASE", "ORGANIZATION", "STATUS", "INCOME_AMT", "SPECIAL_CONSIDERATIONS", "ASK_AMT"
o	What variable(s) should be removed from the input data because they are neither targets nor features?
The variables that were removed from the input data were “NAME” and “EIN” because they are neither targets nor features.

•	Compiling, Training, and Evaluating the Model
o	How many neurons, layers, and activation functions did you select for your neural network model, and why?
I had 3 tries to get the best and accuracy of above 75%.
•	1st try: 3 hidden layers and outer layer: 1st hidden layer includes 88 neurons, relu activation, 2nd hidden layer included 44 neurons, relu activation, 3rd hidden layer 22 neurons, activation, and outer layer: 1 unit, sigmoid activation and adam optimizer for compile and 100 epochs.

•	2nd try: 4 hidden layers and outer layer: 1st hidden layer includes 88 neurons, relu activation, 2nd hidden layer included 44 neurons, relu activation, 3rd hidden layer 22 neurons, activation, 4th hidden layer 11 neurons, activation, relu activation and outer layer: 1 unit and sigmoid activation adam optimizer for compile and 50 epochs.

•	3rd try: 4 hidden layers and outer layer: 1st hidden layer includes 1000 neurons, relu activation, 2nd hidden layer included 500 neurons, sigmoid activation, 3rd hidden layer 250 neurons, sigmoid activation, 4th hidden layer 175 neurons, relu activation, and outer layer: 1 unit and sigmoid activation adam optimizer for compile and 100 epochs.
o	Were you able to achieve the target model performance? The best accuracy was 0.7350 on the 2nd try.
o	What steps did you take in your attempts to increase model performance?
Removing and cleaning neither targets/features within the dataset, trying different numbers of hidden layers, adding a 4th hidden layer, changing the activation type, and the number of epochs

3.	Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.
Within the 3 attempts to get an accuracy of over 75%, I was not able to achieve that result. The higher the number of neurons and the higher number the epochs would have slowed the processor and taken longer to run. I would have added another hidden layer with a lesser number of neurons, lesser number of epochs, and changed the type of activation within the hidden layers this would possible have gotten the accuracy above 75%

1. Overview of the analysis: The purpose of this analysis is the nonprofit foundation Alphabet Soup finds a tool that can help in selecting applicants for funding with the best chance of success in their venture. Using machine learning and neural networks, we can use features within the dataset to predict whether the applicants will be successful if they are funded by Alphabet Soup foundation. 

2. Results: Using bulleted lists and images to support your answers, address the following questions:
•	Data Preprocessing
o	What variable(s) are the target(s) for your model?
The target variable “y” is the “IS_SUCCESSFUL” column.
o	What variable(s) are the features for your model?
The features of the model “X” are "IS_SUCCESSFUL" column as: "APPLICATION_TYPE" , "AFFILIATION", "CLASSIFICATION", "USE_CASE", "ORGANIZATION", "STATUS", "INCOME_AMT", "SPECIAL_CONSIDERATIONS", "ASK_AMT"
o	What variable(s) should be removed from the input data because they are neither targets nor features?
The variables that were removed from the input data were “NAME” and “EIN” because they are neither targets nor features.

•	Compiling, Training, and Evaluating the Model
o	How many neurons, layers, and activation functions did you select for your neural network model, and why?
I had 3 tries to get the best and accuracy of above 75%.
•	1st try: 3 hidden layers and outer layer: 1st hidden layer includes 88 neurons, relu activation, 2nd hidden layer included 44 neurons, relu activation, 3rd hidden layer 22 neurons, activation, and outer layer: 1 unit, sigmoid activation and adam optimizer for compile and 100 epochs.

•	2nd try: 4 hidden layers and outer layer: 1st hidden layer includes 88 neurons, relu activation, 2nd hidden layer included 44 neurons, relu activation, 3rd hidden layer 22 neurons, activation, 4th hidden layer 11 neurons, activation, relu activation and outer layer: 1 unit and sigmoid activation adam optimizer for compile and 50 epochs.

•	3rd try: 4 hidden layers and outer layer: 1st hidden layer includes 1000 neurons, relu activation, 2nd hidden layer included 500 neurons, sigmoid activation, 3rd hidden layer 250 neurons, sigmoid activation, 4th hidden layer 175 neurons, relu activation, and outer layer: 1 unit and sigmoid activation adam optimizer for compile and 100 epochs.
o	Were you able to achieve the target model performance? The best accuracy was 0.7350 on the 2nd try.
o	What steps did you take in your attempts to increase model performance?
Removing and cleaning neither targets/features within the dataset, trying different numbers of hidden layers, adding a 4th hidden layer, changing the activation type, and the number of epochs

3.	Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.
Within the 3 attempts to get an accuracy of over 75%, I was not able to achieve that result. The higher the number of neurons and the higher number the epochs would have slowed the processor and taken longer to run. I would have added another hidden layer with a lesser number of neurons, lesser number of epochs, and changed the type of activation within the hidden layers this would possible have gotten the accuracy above 75%