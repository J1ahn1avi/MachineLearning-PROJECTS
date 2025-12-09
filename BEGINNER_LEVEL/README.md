## Project-1
# Titanic Survival Prediction

This project is a beginner-level machine learning exercise using the Titanic dataset to predict passenger survival. The workflow demonstrates data cleaning, feature engineering, model training, and evaluation using logistic regression.

## Project Structure
- `PROJECT_1_TITANIC_SERVIVAL_PREDICTION.ipynb`: Main Jupyter notebook containing all code and analysis.
- `train_and_test2.csv`: Dataset used for training and testing the model.

## Steps
1. **Data Loading**: Read the Titanic dataset into a pandas DataFrame.
2. **Exploratory Data Analysis (EDA)**: Visualize and understand the data using seaborn and matplotlib.
3. **Data Cleaning**: Handle missing values, drop irrelevant columns, and impute missing ages based on passenger class.
4. **Feature Engineering**: Convert categorical variables (Sex, Embarked) into dummy/one-hot encoded variables.
5. **Model Building**: Split the data into training and testing sets, train a logistic regression model.
6. **Prediction & Evaluation**: Predict survival on the test set and evaluate accuracy.

## Results
- Achieved an accuracy of approximately 75% using logistic regression.
- Demonstrated standard data science workflow for classification problems.

## Requirements
- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## How to Run
1. Open the notebook `PROJECT_1_TITANIC_SERVIVAL_PREDICTION.ipynb` in Jupyter or VS Code.
2. Run each cell sequentially to reproduce the analysis and results.

## Notes
- The project uses basic feature engineering and logistic regression. Accuracy can be improved with more advanced models and techniques.
- Missing values in categorical features are handled by filling with 0 for one-hot encoded columns.

## Author
- Jahnavi Nagulla

---
This project is for educational purposes and demonstrates the end-to-end process of building a simple machine learning model.
