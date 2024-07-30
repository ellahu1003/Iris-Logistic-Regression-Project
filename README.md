# iris_logistic_regression

## Project Overview
This project performs logistic regression on the Iris dataset to classify iris species based on sepal and petal measurements. It involves training a logistic regression model, evaluating its performance using a confusion matrix, and visualizing the results. Techniques include data normalisation, model fitting, and performance evaluation using standard classification metrics.

## Technologies Used
1) Python
2) Pandas
3) NumPy
4) Scikit-Learn
5) Matplotlib
6) Seaborn

## Dataset
The dataset used for this project is `iris.csv`, which contains measurements of sepal length, sepal width, petal length, and petal width for different iris species.

## Project Structure
 ```markdown
iris_logistic_regression/
│
├── data/
│   └── iris.csv
│
├── notebook/
│   └── iris_logistic_regression.ipynb
│
├── results/
│   └── confusion_matrix_iris.png
│   
└── requirements.txt
 ```

## Methodology
1) Data Collection:
   
   The project uses the 'iris.csv' dataset, which is available directly from Scikit-Learn. It includes measurements of sepal length, sepal width, petal length, and petal width for different iris species.

2) Data Preprocessing:
   1. Loading the Data: The dataset is loaded using Pandas, which allows for efficient data manipulation and analysis.
   2. Exploratory Data Analysis: Initial exploration of the dataset is conducted to understand the distribution and relationships between features. This includes visualizing the data using Seaborn
   3. Identify Independent Variables: The independent variables (features) are the sepal and petal measurements: SepalLengthCm, SepalWidthCm, PetalLengthCm, and PetalWidthCm.
   4. Encode Dependent Variable: The dependent variable (species) is encoded such that ‘Iris-setosa’ is encoded as 0, and 'Iris-versicolor' and 'Iris-virginica' are both encoded as 1.

3) Model Building and Training:
   1. Model Initialisation: A logistic regression model is initialised using Scikit-Learn's LogisticRegression class. 
   2. Train-Test Split: The dataset is split into training and test sets using a 25-75 split. The independent variables are stored in X_train and X_test, while the dependent variable is stored in y_train and y_test.

4) Model Evaluation:
   1. Confusion Matrix: A confusion matrix is generated and visualised to compare the predicted labels to the actual labels (gold labels).
   2. Performance Metrics: The model's performance is evaluated using standard classification metrics: Accuracy score, precision and recall.

## Setup and Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/ellahu1003/iris-logistic-regression.git
    cd iris-logistic-regression
    ```
2. Install the required packages:
    ```bash
    pip install -r Requirements.txt
    ```
3. Run the Jupyter Notebook:
    ```bash
    jupyter notebook notebook/Logistic_Regression_Iris.ipynb
    ```

## Requirements
The 'Requirements.txt' file lists all the Python packages required to run the project. Install these dependencies to avoid any compatibility issues.

## Results
1) Accuracy: 1.0
2) Precision: 1.0
3) Recall Score: 1.0
4) The relationship between the predicted and actual values is visualised in confusion_matrix_iris.png.

## Conclusion
1) The logistic regression model achieved perfect accuracy, precision, and recall scores, indicating an excellent fit for this dataset.
2) The confusion matrix shows that all the iris species were correctly classified without any misclassifications.
3) The results suggest that the model is highly reliable for classifying iris species based on the given features.

