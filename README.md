# Titanic Survival Prediction

This project predicts the survival of Titanic passengers using a Decision Tree classifier. The model uses features such as `Pclass`, `Age`, `Fare`, and `Sex_n` to make predictions. The project includes the following steps:

- Exploratory Data Analysis (EDA)
- Data Preprocessing
- Model Training and Evaluation
- Survival Prediction

## Steps:

### 1. **Exploratory Data Analysis (EDA)**
- Visualized the distribution of various features such as `Age`, `Fare`, `Pclass`, and `Sex`.
- Analyzed missing data and the relationship between features and survival.
  
### 2. **Data Preprocessing**
- Handled missing values in `Age` and `Fare` columns.
- Encoded categorical data (e.g., `Sex`) into numerical format.
- Split the dataset into training and testing sets.

### 3. **Model Training**
- Built a Decision Tree classifier using `Pclass`, `Age`, `Fare`, and `Sex_n` features.
- Trained the model on the training data and evaluated it on the test data.

### 4. **Model Evaluation**
- Evaluated model performance using accuracy and confusion matrix.

### 5. **Survival Prediction**
- Predicted survival outcomes for the test dataset.

## Requirements
- Python 3.x
- pandas
- scikit-learn
- matplotlib
- seaborn

## Usage

1. Clone the repository.
2. Ensure the `titanic.csv` dataset is placed in the project directory.
3. Run `titanic_survival_prediction.py` to preprocess the data, train the model, and predict survival.
4. View the results in the output.

## Results
The model's performance is evaluated based on the confusion matrix, showing the true positives, true negatives, false positives, and false negatives.

## License
This project is licensed under the MIT License.
