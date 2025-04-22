#  Phone Price Prediction () Using Machine Learning)
## 1. Problem Statement
Smartphone pricing is influenced by a wide range of features such as RAM, battery capacity, display size, and connectivity options. The objective of this project was to build a classification model to predict the price category of a phone based on its technical specifications.

## 2. Data Analysis
The dataset used contained 21 features, including both numerical and binary categorical variables. Key features impacting price prediction included:
- RAM – Strong correlation with price range
- Battery Power – Important for user experience
- Internal Memory & Storage – Direct influence on cost
- Screen Size – Affects manufacturing cost
- 4G/3G/WiFi Support – Feature-rich devices usually cost more
- Camera Megapixels – Higher specs contribute to pricing

###Insights:
- Devices with higher RAM and battery power often fall into the higher price range.
- Devices without 3G/4G or lower camera specs mostly belong to the lower price category.

3. Data Preprocessing
Missing values: None in the dataset

Feature Scaling: Applied standard scaling for numerical features

Encoding: Binary categorical values retained as-is (0/1)

Train-Test Split: 80% training and 20% testing for evaluation

4. Model Development
Multiple classification models were tested:

Logistic Regression

Decision Tree Classifier

Random Forest Classifier

Support Vector Machine (SVM)

Gradient Boosting Classifier

Best Model:
Random Forest Classifier

Accuracy Achieved: 88%

Chosen for its strong performance in handling nonlinear relationships and feature importance analysis

5. Model Evaluation
Accuracy: 88%

Confusion Matrix: Revealed balanced classification across all categories

Precision/Recall/F1-score: Indicated strong model reliability for real-world application

6. Business Impact
This model can be used by:

E-commerce platforms for categorizing smartphones

Retailers to set price tags for new devices

Market analysts to understand the relationship between features and pricing trends

7. Limitations & Future Work
Current model predicts predefined price ranges, not actual price values

Could be extended using regression models for continuous price prediction

Incorporating brand value and market trends may improve accuracy
