# 🧠 Obesity Risk Prediction using Ensemble Learning

## 📌 Project Overview

This project focuses on predicting **obesity risk levels** using machine learning techniques on a real-world dataset. It explores data analysis, preprocessing, and multiple classification models, with a strong emphasis on **ensemble learning methods** to improve prediction accuracy.

The goal is to classify individuals into different **obesity categories** based on lifestyle, physical, and demographic features.

---

## 🚀 Features

* 📊 Exploratory Data Analysis (EDA) with visualizations
* 🧹 Data preprocessing (handling categorical + numerical data)
* ⚖️ Feature scaling and encoding
* 🤖 Implementation of multiple ML models:

  * K-Nearest Neighbors (KNN)
  * Random Forest
  * Gradient Boosting
* 🔗 Ensemble learning using Voting Classifier
* 📈 Performance evaluation using accuracy, F1-score, and classification report

---

## 🗂️ Dataset

* The dataset contains features like:

  * Age
  * Weight
  * Height
  * Gender
  * Lifestyle habits
* Target variable:

  * **NObeyesdad** (Obesity category)

---

## ⚙️ Tech Stack

* Python 🐍
* Pandas & NumPy
* Matplotlib & Seaborn
* Scikit-learn

---

## 🔍 Workflow

### 1. Data Loading

* Dataset loaded using Pandas
* Google Drive integration used (Colab environment)

### 2. Exploratory Data Analysis

* Distribution plots (weight, age, gender)
* Count plots for obesity classes
* Correlation heatmaps
* Pairplots for feature relationships

### 3. Data Preprocessing

* Handling categorical variables (Encoding)
* Feature scaling using **StandardScaler (Z-score normalization)**
* Feature engineering (Age groups, weight bins)

### 4. Model Building

#### 🔹 KNN Classifier

* Suitable for structured/tabular data
* Uses distance-based classification

#### 🔹 Random Forest

* Ensemble of decision trees
* Handles non-linear relationships effectively

#### 🔹 Gradient Boosting

* Sequential learning model
* Improves weak learners iteratively

---

## 🧠 Ensemble Learning

A **Voting Classifier** is used to combine:

* KNN
* Random Forest
* Gradient Boosting

👉 This improves overall prediction performance by leveraging strengths of multiple models.

---

## 📊 Model Evaluation

Models are evaluated using:

* ✅ Accuracy Score
* ✅ F1 Score
* ✅ Classification Report

---

## 📈 Key Insights

* Obesity is more prominent in certain age groups (e.g., 21–30)
* Lifestyle and physical features strongly influence obesity levels
* Ensemble methods outperform individual models

---

## ▶️ How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the notebook

Open in Jupyter Notebook or Google Colab:

```bash
jupyter notebook PROJECT_Ensemble_learning.ipynb
```

---

## 📁 Project Structure

```
📦 Obesity-Prediction
 ┣ 📜 PROJECT_Ensemble_learning.ipynb
 ┣ 📜 README.md
 ┗ 📜 requirements.txt
```

---

## 💡 Future Improvements

* Hyperparameter tuning
* Deep learning models
* Deployment as a web app (Streamlit / Flask)
* Real-time prediction system

---

## 🤝 Contributing

Feel free to fork the repo and submit pull requests!

---

## 📜 License

This project is open-source and available under the MIT License.

---

## 👩‍💻 Author

**Pragati Garg**

---

⭐ If you found this useful, don't forget to star the repo!
