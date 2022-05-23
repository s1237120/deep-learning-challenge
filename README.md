# deep-learning-challenge

1. **Overview** of the analysis: Explain the purpose of this analysis.
    Purpose of the analysis is to use neural network machine learning algorithm to predict whether or not applicants for funding will be successful. 

2. **Results**: Using bulleted lists and images to support your answers, address the following questions.


  * Data Preprocessing
    * What variable(s) are considered the target(s) for your model?
        IS_SUCCESFUL Column

    * What variable(s) are considered to be the features for your model?
         Columns other than IS_SUCCESFUL

    * What variable(s) are neither targets nor features, and should be removed from the input data?
        Variables in EIN and Name column, Also features that had values less than 500. Lastly target value less than 1000. 

  * Compiling, Training, and Evaluating the Model
    * How many neurons, layers, and activation functions did you select for your neural network model, and why?
        Started off with neurons, with 2 hidden layers, and relu activation funtion as researching online showed relu is better than sigmoid with complicated models. 

    * Were you able to achieve the target model performance?
        No, Target model performance of 75% was not reached. Highest accuracy reached was using simpler relu model yielding 72.9%

    * What steps did you take to try and increase model performance?
        Changing the activation functions, mix and matching activation functions, increasing the hidden layers, number of epochs. 

3. **Summary**: 
    Using Relu with moderate epoch and neuron numbers yield the best result.