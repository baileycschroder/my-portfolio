# Gold Recovery Prediction Project

This project analyzes the gold recovery process and builds machine learning models to predict recovery rates at different stages of mineral processing. The analysis includes data cleaning, handling missing values, exploratory data analysis, feature selection, and model comparison using Linear Regression, Random Forest, and Gradient Boosting. The main evaluation metric is weighted sMAPE, combining rougher and final recovery predictions.

## Project Structure

- `data/`: Contains the datasets (`gold_recovery_train.csv`, `gold_recovery_test.csv`, `gold_recovery_full.csv`)
- `notebooks/`: Jupyter notebook with all analysis and modeling (`gold-recovery-prediction.ipynb`)
- `requirements.txt`: Python dependencies

## How to Run

1. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
2. Place the datasets in the `data/` folder.
3. Open the notebook in Jupyter or VS Code and run the cells.

## Results

- Compared multiple models and selected the best based on weighted sMAPE.
- Achieved project goals for prediction accuracy and data validation.
- See the notebook for detailed metrics, plots, and reviewer feedback.

## Author

Created by Bailey Schroder.
