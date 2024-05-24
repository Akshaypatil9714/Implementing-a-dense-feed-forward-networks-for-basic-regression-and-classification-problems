# Implementing-a-dense-feed-forward-networks-for-basic-regression-and-classification-problems

Datasets

Diabetes Dataset:

The scikit-learn library includes a toy Diabetes dataset consisting of baseline variables for diabetes patients along with a quantitative measure of disease progression one year after baseline.

Ionosphere Dataset:

The UCI Machine Learning Repository includes an Ionosphere dataset of radar returns from the ionosphere, collected by an array of high-frequency antennas. The radar returns are labeled “Good” or “Bad”, based on whether they show evidence of structure in the ionosphere.

Tasks

Regression

Applying Linear Regression

We split the Diabetes dataset into training and testing sets, then constructed a linear regression model using the scikit-learn library. The performance of the model on each set is described below.

Mean Squared Error (MSE): 2418

R2 Score: 0.5

Constructing a Multilayer Perceptron

For this task, we implemented a neural network manually in “vanilla” Python, without using third-party machine learning or statistical modules, except for:

Using scikit-learn to load and split the dataset

Using Matplotlib to plot a learning curve

The neural network consists of two hidden layers, each with two neurons using sigmoid activation, and a single output layer. The chosen loss function was optimized using backpropagation and gradient descent. The learning curve shows the training and test loss as a function of the number of epochs.

Mean Squared Error (MSE): 20822

Test Loss: 478913

Classification

Constructing and Tuning a Model

We designed a dense feed-forward neural network for the UCI Ionosphere dataset, setting aside 88 samples for testing. The overall accuracy of the neural network model was 94%.
