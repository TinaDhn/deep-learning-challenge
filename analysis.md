# deep-learning-challenge

****Overview of the analysis: ****
The non-profit foundation Alphabet Soup wants to create an algorithm to predict whether or not
applicants for funding will be successful.We'll use machine learning and neural networks to analyze the data and create a tool that can predict whether an applicant will succeed if funded by Alphabet Soup.



**Data Preprocessing:**

What variable(s) are the target(s) for your model?
IS_SUCCESSFUL

What variable(s) are the features for your model?
APPLICATION_TYPE
AFFILIATION
CLASSIFICATION
USE_CASE
ORGANIZATION
STATUS
INCOME_AMT
SPECIAL_CONSIDERATIONS
ASK_AMT


What variable(s) should be removed from the input data because they are neither targets nor features?
EIN and NAME—Identification columns removed from the input data because they are neither targets nor features


**Compiling, Training, and Evaluating the Model**

How many neurons, layers, and activation functions did you select for your neural network model, and why?
There were two layers total for each model after applying Neural Networks. The number of hidden nodes were dictated by the number of features.
2 hidden layers with 80, 30 neurons split (the input (node) feature was 43, 80 was chosen as the first layer as it is almost double the input_feature). With an hidden layer activation function of relu as this our go to for first model.

Were you able to achieve the target model performance?
A loss value of 55 indicates that the model can be further optimized.
The accuracy percent shows that 72% of the model's predicted values align with the true values in the original dataset.
I was not able to achieve the 75% model accuracy target

What steps did you take in your attempts to increase model performance?
I experimented with increasing nodes and neurons, with changing other parameters to get a better accuracy but despite doing this both models came below the 75% threshold.


Summary: 
Our Goal was to develop a deep learning model to predict the success of applicants for funding by the nonprofit foundation Alphabet Soup. We performed data preprocessing, compiled, trained, evaluated and munipulated multiple models to achieve the best performance. On the whole, while the model never reached the target accuracy of 75%, it did come quite close at 73% for the best iteration.The Best model used for the final optimization was Automated Tuning Approach none of the other attempted models came close to the desired performance threshold.