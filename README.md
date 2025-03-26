# 🏥 SKIN DISORDER DETECTION USING MACHINE LEARNING

## 🏆 OVERVIEW  
🚀 This project aims to **classify different types of skin disorders** using **machine learning models**.  
🌱 Early diagnosis helps **doctors provide better treatment plans & improve patient outcomes**.

---

## 📂 DATASET  
📸 **Features Analyzed:**  
✅ **Categorical Features** – Symptoms & skin conditions (e.g., erythema, scaling, itching, etc.)  
✅ **Numerical Features** – Patient attributes such as age, severity scores, and other clinical parameters  

📌 **Preprocessing Techniques:**  
🔹 Handling missing values  
🔹 Feature engineering & transformation  
🔹 Normalization & scaling  
🔹 Train-test splitting

---

## ⚡ MODELS USED & PERFORMANCE COMPARISON

### 🔵 **1️⃣ LOGISTIC REGRESSION**  
🛠 **Architecture:**  
✔️ Simple and interpretable model  
✔️ Works well for linearly separable data  

🔹 **Accuracy:** **82%**  
📌 **Insight:** Serves as a good baseline model, though limited in capturing complex patterns.

---

### 🟢 **2️⃣ RANDOM FOREST CLASSIFIER**  
🛠 **Architecture:**  
✔️ Ensemble learning with decision trees  
✔️ Handles non-linearity and complex interactions  

🔹 **Accuracy:** **88%**  
📌 **Insight:** Provides robust performance and insights through feature importance.

---

### 🟡 **3️⃣ SUPPORT VECTOR MACHINE (SVM)**  
🛠 **Architecture:**  
✔️ Effective in high-dimensional spaces  
✔️ Uses kernel tricks for complex decision boundaries  

🔹 **Accuracy:** **85%**  
📌 **Insight:** Reliable model, though computationally intensive on larger datasets.

---

### 🔴 **4️⃣ XGBOOST (BEST MODEL)**  
🛠 **Architecture:**  
✔️ Gradient boosting approach with optimized performance  
✔️ Efficient in handling missing values and feature selection  

🔹 **Accuracy:** **92%** ✅ **Best Performing Model!**  
📌 **Insight:** Outperforms other models with advanced ensemble techniques.

---

## 📊 PERFORMANCE COMPARISON  
| Model                            | Accuracy  |
|----------------------------------|-----------|
| 🔵 **Logistic Regression**       | **82%**   |
| 🟢 **Random Forest**             | **88%**   |
| 🟡 **SVM**                       | **85%**   |
| 🔴 **XGBoost**                   | **92%**   |

📌 **Key Takeaways:**  
✅ **XGBoost (92%)** is the best-performing model.  
✅ **Random Forest (88%)** shows strong performance with non-linear data.  
✅ **SVM (85%)** is effective but computationally intensive.  
✅ **Logistic Regression (82%)** is a reliable baseline.

---

## 🛠 INSTALLATION  
📥 **Install dependencies:**  
```bash
pip install numpy pandas scikit-learn xgboost
