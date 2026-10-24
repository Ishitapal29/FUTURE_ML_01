Sales and Demand Forecasting

Project Overview

This project predicts future grocery sales using historical sales data from the Store Sales – Time Series Forecasting dataset on Kaggle.

Objectives

- Analyze historical sales data.
- Prepare data for machine learning.
- Train and evaluate sales forecasting models.
- Compare model performance.
- Provide insights to support better inventory planning.

Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Kaggle Notebooks

Model Evaluation

The original Random Forest model achieved a Mean Absolute Error (MAE) of 490.77. The improved Random Forest model achieved an MAE of 167.07 on the validation data.

The lower MAE indicates that the improved model performed better on this validation set.

Dataset

Store Sales – Time Series Forecasting, available on Kaggle.

Author

Future Interns – Sales and Demand Forecasting Task

Model Evaluation and Limitations

The improved Random Forest model achieved a Mean Absolute Error (MAE) of 167.07, compared with 490.77 for the original model on the validation sample. This represents an improvement in validation performance.

Limitation: The models were evaluated on a sample of the historical sales data. Their performance may differ when forecasting future sales on unseen data. Further testing is needed before using the predictions for real inventory decisions.
