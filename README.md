Built an end-to-end machine learning project to predict customer churn for a retail bank using a dataset of 10,000 customers.
Key highlights:

Performed EDA, data cleaning, and feature engineering (interaction features, behavioral flags, age/tenure binning)
Handled class imbalance using SMOTEENN (oversampling + cleaning) and downsampling techniques
Trained and compared multiple models: Decision Tree, Random Forest, and Gradient Boosting
Built scikit-learn Pipelines with ColumnTransformer for clean, reproducible preprocessing
Tuned classification threshold (0.30) to optimize recall for the minority (churned) class
Evaluated using ROC-AUC, classification report, and confusion matrix
Saved the final Gradient Boosting model using Pickle for deployment

Tech stack: Python, Pandas, NumPy, Scikit-learn, Imbalanced-learn, Seaborn, Matplotlib
