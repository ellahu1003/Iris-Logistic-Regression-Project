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

## Setup and Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/iris-logistic-regression.git
    cd iris-logistic-regression
    ```
2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the Jupyter Notebook:
    ```bash
    jupyter notebook notebook/Logistic_Regression_Iris.ipynb
    ```
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
## Results
1) Accuracy: 1.0
2) Precision: 1.0
3) Recall Score: 1.0
4) The relationship between the predicted and actual values is visualised in confusion_matrix_iris.png.

## Conclusion
1) The logistic regression model achieved perfect accuracy, precision, and recall scores, indicating an excellent fit for this dataset.
2) The confusion matrix shows that all the iris species were correctly classified without any misclassifications.
3) The results suggest that the model is highly reliable for classifying iris species based on the given features.

