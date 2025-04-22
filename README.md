# Customer-Behavior-Prediction_202401100300188
**1) Overview:**
Customer behavior is a key driver of business strategy and decision-making. This project leverages machine learning techniques to classify customers into two categories: Bargain Hunters and Premium Buyers, based on their purchasing behavior. Additionally, it incorporates unsupervised clustering for customer segmentation to extract deeper insights.
By analyzing key features such as total_spent, avg_purchase_value, and visits_per_month, the project provides a robust framework for understanding and predicting customer buying tendencies.

**2) Key Features:**
- Customer Classification: Uses machine learning models (e.g., Logistic Regression) to predict whether a customer is a 'Bargain Hunter' or 'Premium Buyer'.
- Evaluation Metrics: Calculates accuracy, precision, recall, and visualizes a confusion matrix to assess model performance.
- Clustering and Segmentation: Utilizes KMeans clustering to discover patterns and group customers based on similar behaviors.
- Visualizations: Generates insightful plots, such as heatmaps and scatterplots, to better interpret the findings.

**3) How It Works**
- Data Preparation- The dataset (customer_behavior.csv) is preprocessed to ensure clean and reliable inputs.
- Features such as total_spent, avg_purchase_value, and visits_per_month are used for model training.
- Target variable, buyer_type, is encoded for binary classification.

- Classification- A Logistic Regression model is trained to classify customers based on their purchasing patterns.
- The model's performance is evaluated through metrics such as accuracy, precision, and recall.
- Confusion matrix heatmaps are generated for intuitive performance visualization.

- Clustering- KMeans clustering is applied to identify and segment customer groups.
- Scatterplots are used to visually explore the clusters and understand behavioral trends.

- Output- Predictive insights into customer behavior.
- Identification of customer segments for tailored marketing or strategy refinement.

**4) Technologies and Libraries:**
- Python (Programming Language)
- Pandas and NumPy (Data Manipulation and Analysis)
- Scikit-learn (Machine Learning Models and Utilities)
- Seaborn and Matplotlib (Data Visualization)







