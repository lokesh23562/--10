# 📊 Customer Segmentation & Prediction using Machine Learning

---

## 🚀 Project Overview

This project focuses on analyzing customer data to identify distinct customer segments and build predictive models for each segment. By combining clustering techniques with machine learning models, the project aims to improve business decision-making and customer targeting strategies.

---

## 🎯 Objectives

* Segment customers using clustering algorithms
* Build separate prediction models for each segment
* Evaluate model performance using multiple metrics
* Perform hyperparameter tuning for optimization
* Generate business insights and recommendations

---

## 🛠️ Tech Stack

* **Programming Language:** Python
* **Libraries:**

  * Pandas, NumPy
  * Scikit-learn
  * Matplotlib, Seaborn

---

## 📁 Project Structure

```
customer-segmentation-project/
│
├── customer_segmentation.ipynb   # Main implementation notebook
├── segmentation_data.csv         # Dataset with cluster labels
├── segment_profiles.md           # Description of customer segments
├── model_evaluation_results.csv  # Model performance metrics
├── business_recommendations.pdf  # Final business insights
└── README.md                     # Project documentation
```

---

## 📊 Dataset Information

* **File Name:** `customer_churn.csv`
* **Number of Rows:** 500
* **Number of Columns:** 4
* **Description:** Contains customer information and churn details used for segmentation and prediction.

---

## ⚙️ Installation & Setup

### Step 1: Clone the Repository

```bash
git clone https://github.com/your-username/customer-segmentation-project.git
cd customer-segmentation-project
```

### Step 2: Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### Step 3: Run the Project

```bash
jupyter notebook
```

Open `customer_segmentation.ipynb` and run all cells.

---

## 🔍 Methodology

### 1. Data Preprocessing

* Handling categorical variables using encoding
* Feature scaling using StandardScaler

### 2. Clustering Techniques

* K-Means Clustering
* Hierarchical Clustering
* DBSCAN

### 3. Model Building

* Random Forest Classifier for each customer segment

### 4. Hyperparameter Tuning

* GridSearchCV used to find optimal parameters

### 5. Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC

---

## 📈 Results

### Example Output:

| Segment           | Accuracy | F1 Score |
| ----------------- | -------- | -------- |
| Premium Customers | 92%      | 0.89     |
| Budget Customers  | 88%      | 0.85     |
| Regular Customers | 90%      | 0.88     |

---

## 🧠 Business Insights

* **Premium Customers:** Offer loyalty programs and exclusive deals
* **Budget Customers:** Provide discounts and promotional offers
* **Regular Customers:** Focus on engagement and retention strategies

---

## 📸 Visualizations

The project includes:

* Elbow Method Graph
* Cluster Visualization
* Feature Importance Graphs

---

## ✅ Key Features

✔ Multiple clustering algorithms implemented
✔ Segment-based predictive modeling
✔ Hyperparameter tuning applied
✔ Comprehensive evaluation metrics
✔ Business-oriented insights

---

## 🧪 Testing & Validation

* Train-test split used for validation
* Cross-validation applied in GridSearch
* Performance evaluated using multiple metrics

---

## ⚠️ Limitations

* Small dataset size may limit model generalization
* DBSCAN results depend heavily on parameter tuning
* Assumes static customer behavior

---

## 🔮 Future Improvements

* Use larger real-world datasets
* Apply deep learning models
* Deploy as a web application
* Integrate real-time analytics

---

## 👨‍💻 Author

**Lokesh Bainaboyana**
CSE Student | Machine Learning Enthusiast

---

## ⭐ Conclusion

This project demonstrates how machine learning can be effectively used to segment customers and generate actionable insights, helping businesses improve customer retention and profitability.

---
