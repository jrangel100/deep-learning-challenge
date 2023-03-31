# deep-learning-challenge

Overview of the analysis:
The purpose of this analysis is to develop deep learning models that can classify the success of a charity organization based on various features and applications. The goal is to create accurate and efficient models that can be used for automated classification and analysis.

Results:

Data Preprocessing:
The target features for the models are the application and classification of the charity organizations. The target variable is the is_successful column. The variables that should be removed from the input data are the name and EIN columns as they are not relevant to the classification task.

Compiling, Training, and Evaluating the Models:
I developed three neural network models with varying numbers of neurons, layers, and activation functions. The first model had three hidden layers with 145 nodes, and a combination of sigmoid and ReLu activation functions. The second model had three hidden layers with 214 nodes and the same activation functions as the first model. The third model had two hidden layers with 150 nodes and the same activation functions as the first and second models. All models were trained using appropriate optimizer and loss functions, and evaluated on a separate validation dataset to prevent overfitting.

Although I was not able to achieve the target performance of 75% accuracy, the best model performance was 72.5% accuracy. I attempted several methods to increase the model's performance, including adjusting the number of epochs and the number of nodes and layers in the neural network models. However, these modifications did not significantly improve the model's accuracy.

Summary:
In summary, I have developed three deep learning models that can classify the success of charity organizations based on their applications and classifications. While I was not able to achieve the target performance, I was able to achieve a high level of accuracy in the models.
