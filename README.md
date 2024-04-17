# Financial_Fraud_Detection
The project entails the implementation of machine learning algorithms for credit card fraud detection. Initially, the dataset is unbalanced, with a disparity in the number of fraudulent and non-fraudulent transactions.<br>
<br>
Following dataset balancing, the processed data undergoes preprocessing steps. These steps typically include handling missing values, feature scaling, and encoding categorical variables. Subsequently, three distinct machine learning models are trained on the balanced dataset:<br>

- Logistic Regression: Initially trained without hyperparameters and then fine-tuned with hyperparameter optimization.
- Random Forest: Utilized as an ensemble learning method to build multiple decision trees and make predictions based on the mode of their outputs.
- XGBoost: Employed as an advanced gradient boosting algorithm known for its efficiency and performance. <br>
<br>
Post-training, the models' performance is evaluated using various metrics such as accuracy, precision, recall, and F1-score. These metrics provide insights into the models' effectiveness in identifying fraudulent transactions. Finally, the model with the highest performance is selected to aid financial institutions in fraud detection and prevention efforts.
