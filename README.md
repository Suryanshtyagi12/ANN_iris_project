Iris Species Classification using Perceptron and ANN
This project demonstrates the classification of Iris species using two different models: a simple Perceptron and an Artificial Neural Network (ANN).

Dataset
The project uses the classic Iris dataset, which contains 150 samples of iris flowers with four features: sepal length, sepal width, petal length, and petal width. The dataset has three target classes: setosa, versicolor, and virginica.

Models Used
Perceptron: A simple linear classifier used as a baseline model.
Artificial Neural Network (ANN): A more complex model with hidden layers to capture non-linear relationships in the data.
Project Structure
The notebook includes the following steps:

Data Loading and Exploration: Loading the Iris dataset and performing basic exploratory data analysis (EDA) including checking for missing values, value counts of species, and visualizing the data using a pairplot.
Data Preprocessing:
Separating features (X) and target (y).
Encoding the categorical target variable species into numerical labels using LabelEncoder.
Splitting the data into training and testing sets using train_test_split.
Scaling the features using StandardScaler.
Perceptron Model:
Initializing and training a Perceptron model on the scaled training data.
Evaluating the Perceptron model using accuracy_score and classification_report.
Artificial Neural Network (ANN) Model:
One-hot encoding the target variable for use with the ANN.
Building a Sequential ANN model with Dense layers and ReLU activation, and a Softmax output layer for multi-class classification.
Compiling the ANN model with the Adam optimizer and categorical crossentropy loss.
Training the ANN model on the scaled training data with validation split.
Evaluating the ANN model on the scaled test data.
Plotting the training and validation accuracy over epochs.
Model Saving: Saving the trained ANN model, the scaler object, and the list of column names for future use.
Dependencies
The project requires the following libraries:

numpy
pandas
matplotlib
seaborn
sklearn
tensorflow
You can install the dependencies using pip:
