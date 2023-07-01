# Titanic-Classification

This project focuses on building a system that predicts whether a person would have survived the sinking of the Titanic based on various factors such as socio-economic status, age, gender, and more. The dataset used for this project is the Titanic dataset.

## Dataset Description

The Titanic dataset contains information about passengers on the Titanic, including features such as:

- `Survived`: Whether the passenger survived (0 = No, 1 = Yes)
- `Pclass`: Passenger class (1 = 1st class, 2 = 2nd class, 3 = 3rd class)
- `Sex`: Gender of the passenger
- `Age`: Age of the passenger
- `SibSp`: Number of siblings/spouses aboard
- `Parch`: Number of parents/children aboard
- `Fare`: Passenger fare
- `Embarked`: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

## Code Description

The code in this repository performs the following tasks:

1. **Data Preprocessing**: Cleaning and preprocessing the dataset, handling missing values, and feature engineering.
2. **Exploratory Data Analysis**: Visualizing the data to gain insights and understand patterns.
3. **Model Building**: Building a classification model using the Random Forest algorithm.
4. **Model Evaluation**: Evaluating the model's performance using accuracy, confusion matrix, classification report, ROC curve, and feature importance.
5. **Random Sample Prediction Comparison**: Comparing the actual and predicted survival status for a random sample of passengers.

## Dependencies

The code is implemented in Python using Jupyter Notebook. The following libraries are required:

- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn

Install the dependencies using the following command:

!pip install -r requirements.txt

## Contributing

Contributions to this project are welcome. Feel free to open an issue or submit a pull request with any improvements or additional features.


