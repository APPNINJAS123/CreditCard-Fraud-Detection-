# 🛡️ Credit Card Fraud Detection using Random Forest

This machine learning project focuses on detecting fraudulent credit card transactions using an anonymized dataset. It includes hyperparameter tuning, cross-validation, and model performance visualization

## 📊 Project Highlights

- ✅ Random Forest Classifier with hyperparameter tuning via `RandomizedSearchCV`
- 📈 Stratified K-Fold cross-validation (5-fold) to handle class imbalance
- 🎯 Precision & Recall as performance metrics
- 📉 Learning curve to visualize overfitting/underfitting
- 💾 Model saved using `joblib` for easy reuse



## 🧪 Dataset

- Source: [Credit Card Fraud Detection Dataset on Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- 284,807 transactions
- Highly imbalanced (fraud cases = 492)



## 🚀 How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/<your-username>/creditcard-fraud-detection.git
   cd creditcard-fraud-detection

2. Install Dependencies:
     pip install -r requirements.txt

3.  Open the Notebook:
      jupyter notebook notebook/fraud_detection.ipynb

 
##📈 Learning Curve
  The following plot shows how the model performs with increasing training data:
      ￼PLEASE CHECK THE IMAGES FOLDER FOR THE GRAPH



##💾 Trained Model
   The final trained model is saved as:
     model/rf_model.pkl


##🛠 Tech Stack
	•	Python 3.10+
	•	scikit-learn
	•	pandas, NumPy
	•	joblib
	•	matplotlib, seaborn
	•	tqdm


##🤝 Contributions
     Open to pull requests, improvements, or feedback.

##🧠 Author
   Made with ❤️ by AppNinjas123

