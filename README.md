# ☁️ Marketing Digital Prediction with Machine Learning on Google Cloud Platform

This project demonstrates the application of **Machine Learning** for **Digital Marketing** using **Google Cloud Platform (GCP)**. It focuses on predicting **user spending behavior** and determining whether a user will make a purchase on a tourism website, using **real user behavior data from Google Analytics** stored in **Google BigQuery**.

Developed by **Nowa Analytics**, a consultancy specializing in data-driven business solutions.

---

## 📌 Project Overview

By leveraging **Google Cloud Platform** tools such as **BigQuery** and **Datalab**, this project allows marketing teams to:

* Analyze large-scale user behavior data directly from Google Analytics
* Predict whether a user will spend or not (classification problem)
* Segment users for personalized marketing campaigns
* Apply advanced **Gradient Boosting** techniques using **XGBoost**

This approach enables data-driven decision-making, improves campaign performance, and enhances the user experience on the website.

---

## ⚙️ Project Steps

1. **Data Acquisition & Exploration**

   * Connect to **Google BigQuery** via GCP
   * Query and retrieve user behavior datasets
   * Explore dataset structure, detect patterns, and visualize trends

2. **Data Preprocessing**

   * Handle missing values and inconsistent data
   * Encode categorical variables
   * Perform **downsampling** to balance the dataset
   * Transform raw hits from Google Analytics into user-level features

3. **Modeling**

   * Train classification models to predict if a user will spend:

     * **XGBoost** (main model)
     * Random Forest
     * Logistic Regression
   * Experiment with Gradient Boosting to improve predictive performance

4. **Evaluation**

   * Metrics for classification:

     * Accuracy
     * Precision, Recall, F1-Score
     * Confusion Matrix
     * ROC Curve and AUC

5. **Insights & Segmentation**

   * Identify high-value users and user patterns
   * Segment users based on predicted behavior
   * Recommend marketing strategies and website improvements

---

## 📁 Project Structure

```
📦 marketing-ml-gcp
│
├── data/                 # Raw queries and processed datasets
├── notebooks/            # Jupyter/Datalab notebooks for exploration and modeling
├── src/                  # Python scripts
│   ├── preprocessing.py
│   ├── modeling.py
│   └── evaluation.py
├── results/              # Visualizations, metrics, and reports
├── README.md             # This file
└── requirements.txt      # Python dependencies
```

---

## 📊 Technologies & Libraries

* **Python 3.9+**
* Google Cloud Platform (BigQuery, Datalab)
* Pandas, NumPy
* Scikit-learn, XGBoost
* Matplotlib, Seaborn
* Imbalanced-learn (for downsampling)
* Jupyter Notebook

---

## ✅ Results

* Accurate prediction of **user spending behavior** (will spend / won’t spend)
* Segmentation of users for **personalized marketing campaigns**
* Insights to improve website user experience
* Demonstrated performance gains using **XGBoost** and Gradient Boosting

---

## 🏢 About Nowa Analytics

**Nowa Analytics** is a data consultancy focused on advanced analytics and AI solutions to optimize business performance. We specialize in marketing analytics, customer behavior prediction, and data-driven strategy.

📍 São Paulo, Madrid, and London
🌐 [nowaanalytics.com](http://nowaanalytics.com) *(replace with real link if available)*

---

## 📬 Contact

For consulting services or more information:

* 📧 [contact@nowaanalytics.com](mailto:contact@nowaanalytics.com)
* 💼 LinkedIn: [Nowa Analytics](https://linkedin.com/company/nowaanalytics)


