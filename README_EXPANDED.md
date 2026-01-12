# Dengue Prediction - Expanded Project

This project expands upon the IEEE paper **"Artificial Intelligence-Based Early Detection of Dengue Using CBC Data"**.

## Features Implemented
1.  **Paper Replication**: Stacking Ensemble (XGBoost + Logistic Regression + MLP -> LightGBM Meta-learner).
2.  **Expansion 1**: Hyperparameter Tuning using `GridSearchCV`.
3.  **Expansion 2**: Deep Learning Model Implementation (Custom Keras DNN).
4.  **Comparison**: Visual comparison of model accuracies.

## How to Run in Google Colab

1.  **Download Files**:
    *   Download `Dengue_Prediction_Expanded.ipynb` from this repository.
    *   Download `CBC Report.csv` (the dataset) from this repository.

2.  **Open Google Colab**:
    *   Go to [https://colab.research.google.com/](https://colab.research.google.com/).
    *   Click **File** -> **Upload notebook**.
    *   Upload the `Dengue_Prediction_Expanded.ipynb` file.

3.  **Upload Dataset**:
    *   In the Colab notebook interface, click on the **Folder icon** (Files) on the left sidebar.
    *   Click the **Upload** button (file icon with an upward arrow).
    *   Select and upload `CBC Report.csv`.

4.  **Run the Notebook**:
    *   Click **Runtime** -> **Run all** (or press `Ctrl+F9`).

## Dependencies
The notebook installs/imports the following:
*   `pandas`, `numpy`, `matplotlib`, `seaborn`
*   `scikit-learn` (Stacking, RandomForest, MLP, LR, Metrics)
*   `xgboost`, `lightgbm`
*   `tensorflow`, `keras`
*   `imblearn` (SMOTE)

## Expected Output
*   Data analysis and missing value handling.
*   Performance metrics (Accuracy, Classification Report) for the Stacking Model.
*   Best parameters found for XGBoost via Hyperparameter Tuning.
*   Training logs for the Deep Learning model.
*   A bar chart comparing the accuracy of the Stacking Ensemble, Tuned XGBoost, and Deep Learning model.
