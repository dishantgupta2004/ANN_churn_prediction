# Customer Churn Prediction using ANN

This project is focused on predicting customer churn using an Artificial Neural Network (ANN) model. It uses the **Churn_Modelling.csv** dataset and provides an easy-to-use web interface built with **Streamlit**.

---

## Project Structure

ANN_CLASSIFICATION/ ├── logs/ ├── app.py ├── Churn_Modelling.csv ├── experiments.ipynb ├── hyperparametertuning.ipynb ├── label_encoder_gender.pkl ├── onehot_encoder_geo.pkl ├── model.h5 ├── prediction.ipynb ├── README.md ├── requirements.txt └── scaler.pkl


---

## How to Run

1. **Clone the Repository**
```bash
git clone <repository-url>
cd ANN_CLASSIFICATION
Create a Virtual Environment

python -m venv venv
source venv/bin/activate   # On MacOS/Linux
venv\Scripts\activate      # On Windows
Install Dependencies

bash

pip install -r requirements.txt
Run the Streamlit App

bash
streamlit run app.py
Model Details
Algorithm: Artificial Neural Network (ANN)

Frameworks Used:

TensorFlow / Keras (for ANN model)

Scikit-learn (for preprocessing like scaling, encoding)

Streamlit (for deployment)

Preprocessing:

Label Encoding for Gender

One-Hot Encoding for Geography

Feature Scaling using StandardScaler

Output: Predicts whether a customer is likely to churn or not.

Notebooks
experiments.ipynb: Model experiments and performance evaluations.

hyperparametertuning.ipynb: Hyperparameter tuning with GridSearchCV or manual tuning.

prediction.ipynb: Making predictions on unseen data.

Features
Upload customer data and get instant churn predictions.

Visualizations for model insights.

Evaluation metrics like Accuracy, Confusion Matrix, etc.

Hyperparameter tuning support.

Requirements
streamlit

tensorflow

scikit-learn

pandas

numpy

matplotlib

seaborn

(Refer to requirements.txt for complete list.)

Author
Dishant gupta

Feel free to connect!







