# Deep-Learning-Challenge

1. **Overview** of the analysis: Explain the purpose of this analysis.

  The analysis utilizes deep learning and neural networks to predict if the applicants for funding will be successful.  The features provided in the dataset are used to create a binary classifer to predict whether applicants will be successful.


2. **Results**: 

  * Data Preprocessing
    * What variable(s) are considered the target(s) for your model?
    The IS_SUCCESSFUL column was considered as the target variable for the model
     
     
    * What variable(s) are considered to be the features for your model?
    All columns besides IS_SUCESSFUL as well as the columns that were dropped (EIN and NAME) were considered as feature variables for the model.
     
     
    * What variable(s) are neither targets nor features, and should be removed from the input data?
    The EIN and NAME columns were dropped and therefore not considered as target or feature variables for the model
      
  * Compiling, Training, and Evaluating the Model
    * How many neurons, layers, and activation functions did you select for your neural network model, and why?
    I had 25 neurons in the first hidden layer of the model and 50 neurons for the second hidden layer.  The activation function used was "relu" and for the output layer the "sigmoid" function was utilized in the model.  
    
    
    * Were you able to achieve the target model performance?
    No, the model was not able to achieve target performance of 75%.  The model achieved an accuracy of 72.66%.


    * What steps did you take to try and increase model performance?
    In Model 2, a third hidden layer was added. However, the model accuracy decreased slightly to 72.43%. 
    In Model 3, the activation function was changed from "relu" to "tanh" for the hidden layers.  The model accuracy was 72.47%
    In Model 4, the number of nodes for the first hidden layer was changed from 25 to 10 and for the second hidden layer the number of nodes were changed from 50 to 20.  Also the number of epochs were changed from 100 to 50. The model accuracy was 72.62%.


3. **Summary**: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.
