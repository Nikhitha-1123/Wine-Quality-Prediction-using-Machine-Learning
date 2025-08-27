# PROJECT : 🍷 Wine Quality Prediction using Machine Learning

This project focuses on predicting the quality of red wine based on physicochemical attributes using multiple classification models. The goal is to analyze key chemical properties and apply machine learning classifiers to predict wine quality effectively.

### 📂 Dataset Used

- `WineQT.csv`: Contains chemical properties of red wines and corresponding quality scores (ranging from 3 to 8).


### 📌 Key Concepts Covered

- **Classifier Models**: Random Forest, Stochastic Gradient Descent (SGD), Support Vector Classifier (SVC)
- **Chemical Analysis**: Focus on density, acidity, alcohol, sulphates, etc.
- **Data Handling**: Pandas and NumPy for cleaning and manipulation
- **Visualization**: Correlation heatmaps, boxplots, and confusion matrices using Seaborn and Matplotlib


### 🛠️ Project Workflow

1. Data Loading & Exploration
2. Data Cleaning and Feature Selection
3. Exploratory Data Analysis (EDA)
4. Feature Scaling using StandardScaler
5. Train-Test Split
6. Model Training:
   - Random Forest Classifier
   - SGD Classifier
   - SVC (Support Vector Classifier)
7. Model Evaluation:
   - Classification Report
   - Confusion Matrix
   - Feature Importance
   - Cross-Validation (Optional)



### 📈 Model Evaluation

Each model was evaluated using classification metrics such as:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix



### 🔍 Feature Importance

The Random Forest classifier revealed that `alcohol`, `sulphates`, and `volatile acidity` were among the most influential factors in predicting wine quality.



### 📌 Requirements

- Python 3.x
- Pandas, NumPy
- Matplotlib, Seaborn
- scikit-learn
