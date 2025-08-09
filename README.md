## **📊 Students Performance Dataset - EDA**

### **📌 Project Overview**

This project explores the **Students Performance Dataset** to uncover insights about students’ academic performance, test preparation, and socio-demographic factors.

**Goal:**

* Understand how different factors (gender, parental education, test preparation, etc.) influence scores in math, reading, and writing.
* Visualize trends, relationships, and patterns in the data.

---

### **🗂 Dataset Information**

* **Source:** [Kaggle - Students Performance Dataset](https://www.kaggle.com/spscientist/students-performance-in-exams)
* **Rows:** 1000
* **Columns:** 8
* **Features:**

  * `gender` — Male/Female
  * `race/ethnicity`
  * `parental level of education`
  * `lunch` — Standard/Free or reduced
  * `test preparation course` — Completed/None
  * `math score`
  * `reading score`
  * `writing score`

---

### **⚙️ Tools & Libraries**

* **Python** 🐍
* **Pandas** – Data manipulation
* **Matplotlib & Seaborn** – Visualization
* **NumPy** – Numerical operations

---

### **📊 EDA Highlights**

#### **1️⃣ Data Cleaning**

* Checked for **missing values** ✅
* Handled **categorical encoding** where necessary
* Removed inconsistencies (e.g., `None` → `Not Completed` in test prep)

#### **2️⃣ Univariate Analysis**

* **Categorical:** Countplots for gender, parental education, lunch type
* **Numerical:** Histograms for math, reading, and writing scores

#### **3️⃣ Bivariate Analysis**

* Gender vs Scores comparison
* Effect of **test preparation course** on scores
* Correlation heatmap between numerical features

#### **4️⃣ Multivariate Analysis**

* Combined influence of parental education + test preparation on scores


### **🚀 How to Run**

```bash

# Install dependencies
pip install -r requirements.txt

# Run the Jupyter Notebook
jupyter notebook student_performance_eda.ipynb
```

---

### **📢 Future Work**

* Predicting student scores using machine learning
* Adding more datasets for broader analysis

---

### **📝 Author**

**Your Name**
💼 [LinkedIn](https://www.linkedin.com/in/anamta-siddiqui-a1776a227/) 

---

