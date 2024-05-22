# deep-learning-challenge
•OVERVIEW

This project aims to develop a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.
we will use the features given in the dataset and use machine learning methods to train and assess the models performance. Th objective is to optimize the model to attain accuracy of 75%

•RESULTS
 
  Data Preprocessing
  
    • Target Variables : IS_SUCCESSFUL
    
    • Feature Variables: 	APPLICATION_TYPE, AFFILIATION,	CLASSIFICATION,	USE_CASE,	ORGANIZATION,	STATUS,	INCOME_AMT,	SPECIAL_CONSIDERATIONS,	ASK_AMT	IS_SUCCESSFUL
    
    • Removed Variables: EIN, NAME
    

  Compiling, Training, and Evaluating the Model
     At first, i use 3 layers, an input layer , a second layer and an output layer. The first two hidden layer, i use the relu activation function and for the outer layer, i use the sigmoid activation function. for the optimization tanh activation function also used.

    Optimization Attempt
        i use three model layers for the optimization, the first attempt is to add a third layer with more nodes. The second attempt is to use a differnt learning rate.
        And the third attempt is to use a droput of 0.5 for each layer. 
        The above methods we use to increase the model performance.

•SUMMARY

    •By using all these methods, i couldnt attain the target accuracy 75%. The accuracy i achieved is 72.78%.

Recommendation

    •i would recommend increasing the number of neurons. or maybe using a different classification such as Random Forest improve the models performance.


        

