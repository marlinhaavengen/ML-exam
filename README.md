# Binary Classification of Habitable Exoplanets

**Description/Abstract:**
Machine learning algorithms hold significant promise for effective binary classification. Achieving reliable outcomes, however, requires addressing several key factors. This study aims to investigate the potential habitability of exoplanets utilizing various machine learning models. Data for this analysis was sourced from NASA's Exoplanet Archive and the Planetary Habitability Laboratory. Thorough data preprocessing was conducted, including addressing notable class imbalance using the Synthetic Minority Over-sampling Technique (SMOTE) to generate synthetic data points for the minority class.

Four models were implemented: Logistic Regression (as the baseline), Decision Tree, Random Forest, and Extreme Gradient Boosting. Key features were identified to reduce model complexity based on their influence on the target variable. Hyperparameter tuning was performed using Grid Search for optimization. The models were primarily evaluated using the macro average F1 score due to the significant class imbalance. Additionally, performance metrics such as accuracy, precision, and recall were compared in detail. 

The results indicated that Extreme Gradient Boosting outperformed the other models in this classification task, demonstrating superior overall consistency based on the evaluation metrics. 

**Keywords: Binary Classification, Habitability, SMOTE, Decision Tree, Random Forest, Extreme Gradient Boosting**
