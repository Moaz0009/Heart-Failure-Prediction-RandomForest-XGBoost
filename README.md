# Heart Failure Prediction using RandomForest and XGBoost

## Overview

This repository contains a project focused on predicting heart failure using machine learning models, specifically RandomForest and XGBoost. The project utilizes various data preprocessing techniques and model evaluation metrics to achieve reliable predictions.

## Contents

- `Heart Failure Prediction (RandomForest - XGBoost).ipynb`: The main Jupyter notebook containing the data analysis, model training, and evaluation processes.
- `README.md`: This file, providing an overview of the project.

## Dataset

The dataset used in this project contains information related to patients' medical conditions and health metrics, which are essential for predicting the likelihood of heart failure. Key features include age, gender, blood pressure, cholesterol levels, and more.

## Models Used

### 1. RandomForest
RandomForest is an ensemble learning method based on decision trees. It builds multiple decision trees during training and outputs the mode of the classes (for classification) or mean prediction (for regression) of the individual trees.

### 2. XGBoost
XGBoost (Extreme Gradient Boosting) is a scalable and accurate implementation of gradient boosting machines. It is widely used for structured/tabular data and known for its performance and efficiency.

## Project Workflow

1. **Data Preprocessing**: 
   - Handling missing values.
   - Feature engineering.
   - Splitting the data into training and testing sets.

2. **Model Training**:
   - Training the RandomForest and XGBoost models.
   - Hyperparameter tuning for model optimization.

3. **Model Evaluation**:
   - Evaluation of the models using metrics such as accuracy, precision, recall, and AUC-ROC.
   - Cross-validation and confusion matrix analysis.

4. **Prediction**:
   - Using the trained models to predict heart failure on new data.
   - Interpretation of results.

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/Moaz0009/heart-failure-prediction.git
   ```

2. Navigate to the project directory:
   ```bash
   cd heart-failure-prediction
   ```

3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

4. Open the Jupyter notebook:
   ```bash
   jupyter notebook "Heart Failure Prediction (RandomForest - XGBoost).ipynb"
   ```

5. Run all cells in the notebook to reproduce the results.

## Dependencies

- Python 3.x
- Jupyter Notebook
- Scikit-learn
- XGBoost
- Pandas
- Numpy
- Matplotlib
- Seaborn

## Results

The models were evaluated on various metrics to determine their effectiveness in predicting heart failure. The XGBoost model showed superior performance compared to the RandomForest model.

## Conclusion

This project demonstrates the application of machine learning models to predict heart failure. Both RandomForest and XGBoost were effective, with XGBoost providing slightly better results. The notebook includes detailed explanations and code to help others understand and replicate the analysis.

## Contributing

If you'd like to contribute to this project, please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
