🌸 Iris Species Classification using Perceptron and ANN
This project demonstrates the classification of Iris flower species using two machine learning models:

Perceptron (Linear Model)

Artificial Neural Network (ANN)

📊 Dataset
The project uses the classic Iris dataset, which contains:

150 samples of iris flowers

4 features:

Sepal Length

Sepal Width

Petal Length

Petal Width

3 target classes:

Setosa

Versicolor

Virginica

🧠 Models Used
Model	Description
Perceptron	A simple linear classifier used as a baseline model.
ANN (Artificial Neural Network)	A deep learning model with hidden layers capable of learning non-linear patterns.
📂 Project Workflow / Structure
✅ 1. Data Loading & Exploration
Load the Iris dataset

Perform EDA:

Check missing values

Count species values

Visualize data using Seaborn pairplot

✅ 2. Data Preprocessing
Separate features (X) and target (y)

Encode species labels using LabelEncoder

Split dataset using train_test_split

Scale features using StandardScaler

✅ 3. Perceptron Model
Initialize and train Perceptron

Evaluate using accuracy_score and classification_report

✅ 4. Artificial Neural Network (ANN)
One-hot encode labels

Build Sequential ANN:

Dense layers + ReLU activation

Softmax output layer for multi-class classification

Compile using Adam optimizer & categorical_crossentropy loss

Train with validation split

Plot training & validation accuracy

✅ 5. Model Saving
Save:

Trained ANN model (model.keras)

Scaler object

Feature (column) names

📦 Dependencies
Install required libraries using:

pip install numpy pandas matplotlib seaborn scikit-learn tensorflow

