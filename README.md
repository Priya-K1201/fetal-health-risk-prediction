# 👶 Fetal Health Risk Prediction using Machine Learning

A machine learning-based healthcare application that predicts fetal health conditions using **Cardiotocography (CTG)** data. The project applies supervised learning algorithms to classify fetal health into **Normal, Suspect, and Pathological** categories, along with exploratory data analysis, clustering, and interactive Tableau visualization.

---

## 📊 System Workflow

The fetal health prediction system follows the workflow below:

**CTG Dataset → Data Preprocessing → Outlier Detection → Exploratory Data Analysis → Feature Scaling → Model Training → Model Evaluation → Fetal Health Prediction → Data Visualization**

Additionally, **K-Means Clustering** is used to identify natural groupings within the dataset, and **Tableau** is used to build an interactive dashboard for visual analysis.

---

## 🎯 Objective

To develop a machine learning model that accurately predicts fetal health conditions from CTG recordings, assisting healthcare professionals in identifying potential fetal risks through data-driven analysis.

---

## ✨ Features

* 🤖 Fetal health classification using Machine Learning
* 📊 Exploratory Data Analysis (EDA)
* 📉 Correlation analysis of CTG features
* 📈 Class distribution visualization
* 🔍 Outlier detection using the IQR method
* 📍 K-Means clustering for pattern analysis
* 📋 Model performance evaluation using Accuracy, Precision, Recall, and F1-Score
* 📊 Confusion Matrix analysis
* 📂 Interactive Tableau dashboard for visualization
* ✅ Sample prediction for new fetal health records

---

## 🧠 Machine Learning Models

The following machine learning algorithms were implemented and evaluated:

* Logistic Regression
* K-Nearest Neighbors (KNN)
* K-Means Clustering (Unsupervised Learning)

The best-performing classification model is selected automatically based on the **F1-Score**.

---

## 👶 Fetal Health Classes

| Class | Description  |
| ----- | ------------ |
| 1     | Normal       |
| 2     | Suspect      |
| 3     | Pathological |

---

## 📂 Dataset

**Dataset:** Fetal Health Classification Dataset

**Source:** Kaggle

The dataset is derived from **Cardiotocography (CTG)** recordings and includes fetal heart rate measurements, accelerations, fetal movements, uterine contractions, and several statistical features used for fetal health assessment.

---

## 🛠 Technologies Used

| Technology   | Purpose                               |
| ------------ | ------------------------------------- |
| Python       | Programming Language                  |
| Pandas       | Data Manipulation                     |
| NumPy        | Numerical Computing                   |
| Matplotlib   | Data Visualization                    |
| Scikit-learn | Machine Learning Models               |
| Tableau      | Interactive Dashboard & Visualization |

---

## ⚙️ Working Principle

* Load the fetal health dataset.
* Detect and remove potential outliers using the Interquartile Range (IQR) method.
* Analyze feature relationships using correlation analysis.
* Visualize class distribution.
* Split the dataset into training and testing sets.
* Standardize features using `StandardScaler`.
* Train Logistic Regression and KNN classifiers.
* Evaluate each model using Accuracy, Precision, Recall, and F1-Score.
* Select the best-performing model.
* Generate confusion matrix and prediction results.
* Apply K-Means clustering to visualize natural data groupings.
* Build an interactive Tableau dashboard for additional insights.

---

## 📁 Repository Structure

```text
fetal-health-risk-prediction/
│
├── README.md
├── requirements.txt
├── .gitignore
│
├── data/
│   ├── fetal_health.csv
│   └── dataset_info.txt
│
├── src/
│   └── fetal_health_prediction.py
│
├── tableau/
│   └── Fetal_Tableau dashboard.twbx
│
├── results/
│   ├── correlation_matrix.png
│   ├── class_distribution.png
│   ├── clustering_visualization.png
│   ├── model_performance.png
│   └── sample_feature_pattern.png
│
├── screenshots/
│   ├── tableau_dashboard.png
│
└── docs/
    └── DS abstract.pdf
```

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/fetal-health-risk-prediction.git
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Project

Execute the Python script:

```bash
python src/fetal_health_prediction.py
```

The program performs preprocessing, trains the models, evaluates performance, displays visualizations, and predicts fetal health conditions.

---

## 📊 Results

* Successfully classified fetal health conditions into three categories.
* Compared Logistic Regression and KNN classifiers.
* Selected the best-performing model using F1-Score.
* Performed K-Means clustering to analyze hidden data patterns.
* Developed an interactive Tableau dashboard for visual exploration of fetal health data.

---

## 🔮 Future Improvements

* Implement advanced ensemble learning models such as Random Forest and XGBoost.
* Explore Deep Learning approaches for improved prediction accuracy.
* Deploy the model as a web application.
* Integrate real-time hospital CTG data.
* Enhance dashboard interactivity with live prediction capabilities.

---

## 👩‍💻 Team Members

* **Priya Dharshini K** – Data Preprocessing, Machine Learning Model Development, Data Analysis, Documentation
* **Teammate 2** – Data Visualization, Tableau Dashboard Development, Testing

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 🙏 Acknowledgments

Special thanks to the faculty mentors and the Department of Electronics and Communication Engineering, **Sri Sivasubramaniya Nadar College of Engineering (SSNCE)**, for their guidance, support, and encouragement throughout this project.
