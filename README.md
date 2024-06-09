## Rock vs Mine Prediction System

This is a supervised machine learning project that predicts whether an object detected underwater is a rock or a mine using a logistic regression model.

### About the Dataset
The dataset used for this project is the [Sonar Dataset](https://www.kaggle.com/datasets/mayurdalvi/sonar-mine-dataset) available on Kaggle. It consists of sonar signals bounced off a metal cylinder (mine) and a cylindrical rock. The dataset contains features obtained from these signals.

### Dependencies
Ensure you have the following dependencies installed:
- pandas
- numpy
- scikit-learn
- matplotlib

### Usage
1. **Importing Dependencies**: This section imports the necessary libraries and tools for data manipulation, model training, evaluation, and visualization.
2. **Loading Data**: The dataset is loaded into a pandas DataFrame from a CSV file.
3. **Data Exploration**: Basic exploratory data analysis is performed to understand the structure and characteristics of the dataset.
4. **Data Preprocessing**: Data is separated into features (X) and labels (Y). Additionally, a train-test split is performed to evaluate the model's performance.
5. **Training the Model**: Logistic Regression model is trained on the training data.
6. **Evaluation**: Model accuracy is evaluated on both the training and test datasets.
7. **Prediction System**: An example input data is provided, and the model predicts whether it represents a rock or a mine.

### How to Run
1. Ensure all dependencies are installed.
2. Download the Sonar Dataset from the provided link.
3. Place the dataset file (`sonar data.csv`) in the appropriate directory.
4. Run the provided code in a Python environment.

### Notes
- The dataset contains two classes:
  - "M" - Mine
  - "R" - Rock
- The model's accuracy is assessed using the accuracy score metric.

Feel free to explore and modify the code according to your requirements.
