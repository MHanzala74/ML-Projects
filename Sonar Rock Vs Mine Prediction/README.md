# Rock vs Mine Prediction using Sonar Data

This project is a binary classification machine learning task that predicts whether a sonar signal is bounced off a **rock** or a **mine**. The model is trained on the well-known **Sonar dataset**.

## 📂 Project Structure

- `Rock_vs_mine_prediction.ipynb` — Jupyter Notebook with the complete data analysis, preprocessing, model training, and evaluation.
- `Copy of sonar data.csv` — The dataset used for training and testing.

## 📊 Dataset Information

The dataset consists of 208 instances, each with 60 numeric features. These features represent energy values of sonar signals reflected off objects. Each instance is labeled as:
- `R` for Rock
- `M` for Mine

### Source
The dataset is taken from the UCI Machine Learning Repository.

## 🧠 Model Overview

The notebook includes the following steps:
- Data loading and exploration
- Feature scaling
- Label encoding
- Train-test split
- Model training using **Logistic Regression**
- Model evaluation using accuracy score

## ✅ Results

The model achieves high accuracy in predicting whether the object is a rock or a mine using sonar signal data.

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/MHanzala74/ML-Projects.git
   cd ML-Projects

