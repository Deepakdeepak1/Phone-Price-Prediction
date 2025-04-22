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

### Insights:
- Devices with higher RAM and battery power often fall into the higher price range.
- Devices without 3G/4G or lower camera specs mostly belong to the lower price category.

## 3. Data Preprocessing
- Missing values: None in the dataset
- Feature Scaling: Applied standard scaling for numerical features
- Encoding: Binary categorical values retained as-is (0/1)
- Train-Test Split: 80% training and 20% testing for evaluation

## 4. Model Development
- Multiple classification models were tested:
- Logistic Regression
- Random Forest Classifier

## Best Model:
- Random Forest Classifier
- Accuracy Achieved: 88%
Chosen for its strong performance in handling nonlinear relationships and feature importance analysis

## 5. Model Evaluation
- Accuracy: 88%
- Precision/Recall/F1-score: Indicated strong model reliability for real-world application

## Conclusion:
The project successfully demonstrated how machine learning can be applied to predict smartphone price categories based on their specifications. The model can assist smartphone retailers or e-commerce platforms in automatic pricing or categorization of devices.
