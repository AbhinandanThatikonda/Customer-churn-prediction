# Bank Customer Churn Prediction (ML & DL)

This project predicts whether a bank customer is likely to churn (i.e., leave the bank) using supervised learning techniques. It involves data cleaning, preprocessing, model training using both Scikit-learn and TensorFlow, hyperparameter tuning, and performance comparison.

## 📌 Highlights

- Dropped unnecessary columns and handled null values
- Applied One-Hot Encoding for categorical features
- Used MinMaxScaler to scale numerical features
- Handled class imbalance using **over-sampling** techniques
- Built two model pipelines:
  - **Scikit-learn**: Tuned various classifiers, selected the best (RandomForest)
  - **TensorFlow**: Built 3 neural networks using ReLU and Sigmoid activations

## 🧰 Tech Stack

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (RandomForestClassifier, Hyperparameter tuning)
- TensorFlow / Keras
- Jupyter Notebook

## 🔍 Dataset Features

- CreditScore
- Geography
- Gender
- Age
- Tenure
- Balance
- NumOfProducts
- HasCrCard
- IsActiveMember
- EstimatedSalary
- Exited (Target: 1 - Churned, 0 - Stayed)

## ⚙️ Model Evaluation

| Model                  | Accuracy |
|-----------------------|----------|
| RandomForest (Sklearn)| ~87%     |
| Neural Network (Keras)| ~82%     |

> Random Forest performed better after hyperparameter tuning on the balanced dataset.

## 📬 Contact
If you have any questions or suggestions, feel free to reach out:

📧 Email: abhinandan1903@gmail.com

🔗 LinkedIn: www.linkedin.com/in/abhinandan1903
