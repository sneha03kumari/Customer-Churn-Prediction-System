# Customer Churn Prediction
Customer churn means when customers stop using a company’s service. It’s important for businesses to know which customers might leave so they can try to keep them.This project uses customer data and feedback to predict churn. It also checks the feelings (sentiment) in the feedback using a tool called TextBlob. Then, it uses machine learning and deep learning to make #predictions. This helps companies understand their customers better and reduce churn.

# Features
- 🧠 Sentiment Extraction using TextBlob
- 📈 Numeric Features like tenure, monthlycharges, totalcharges
- 👴 Demographic Feature: seniorcitizen
- 🏷️ Categorical Features: gender, partner, contract, internetservice, etc.
- 🧩 One-Hot Encoding for categorical variables
- 📊 Feature Scaling with StandardScaler

# Project Workflow
-📥 Data Loading
Load churn dataset from CSV file.
-🧹 Data Preprocessing
Clean column names
Fill missing values
Add dummy feedback if customerfeedback column is missing
-🧠 Sentiment Analysis
Extract sentiment score from feedback using TextBlob
-🗂 Feature Engineering
Drop original text column
One-hot encode categorical features
Normalize numeric values
-📊 Split Dataset
Train-Test split using train_test_split (80% train, 20% test)
-📏 Feature Scaling
Standardize features using StandardScaler
-📈 Model Training
Logistic Regression (baseline model)
Deep Learning (using TensorFlow and Keras)
-📉 Model Evaluation
Accuracy, Classification Report, Confusion Matrix
Training/Validation Accuracy and Loss Plots
-📈 Optional Visualizations
Confusion matrix heatmap, training curves

# Models Used
Model Type	Details
Logistic Regression	Simple, interpretable baseline model
Deep Learning (Neural Network)	3-layer feed-forward model with dropout and ReLU activations
Sentiment Analysis Tool	TextBlob for extracting polarity score from customer feedback
