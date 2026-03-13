# ML_project

## Forecasting property prices in the United States
*Predictive data analysis*

### Project objective
The objective of this project was to compare the performance of several predictive models in order to identify the one with the best predictive ability. The study aimed to predict property prices in the United States based on their different characteristics. 

### Methodology
Following a data cleaning and standardisation phase, the dataset was divided into two subsets: a training dataset (80%) and a test dataset (20%). 
An initial linear regression model was estimated to provide a basis for comparison. The model’s performance was evaluated using the Root Mean Squared Error (RMSE) and the Mean Absolute Error (MAE). Next, Ridge regression was used to introduce a penalty on the coefficients in order to limit the risk of overfitting. Finally, three neural networks were trained using a Multilayer Perceptron Regressor. For example, one of the networks comprises two hidden layers of 100 and 50 neurons, using a ReLU activation function and an Adam optimisation algorithm. The model was trained over several thousand iterations, and the loss curve was used to monitor the convergence of the learning process
