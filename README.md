# 💳 SVM-Based Creditworthiness Classification

This project demonstrates the use of a **Support Vector Machine (SVM)** to classify bank customers as **creditworthy or not** using two key financial indicators: **Income-to-Debt Ratio** and **Credit Utilization**. The model is trained on a synthetically generated dataset created for academic and learning purposes.

---

## 📂 Dataset Overview

- **IncomeToDebtRatio**: Ratio of a customer's income to total debt obligations  
- **CreditUtilization**: Percentage of available credit currently in use  
- **Creditworthy (Target Label)**:  
  - `1` → Creditworthy  
  - `-1` → Not Creditworthy  

Total records: **300 rows × 3 columns**

---

## ⚙️ Tools & Libraries

- **Python 3.x**  
- `pandas`, `numpy`  
- `scikit-learn` (SVC)  
- `matplotlib`, `seaborn`

---

## 🧠 Model Details

- Algorithm: **Support Vector Classification (SVC)**
- Kernel: **Linear**
- Accuracy on Test Set: **100% (synthetic data)**

### 🔍 Model Steps:
1. Data cleaning and feature selection  
2. Train-test split  
3. SVM training using `SVC(kernel='linear')`  
4. Model evaluation using `classification_report`  
5. Visualization of:
   - Decision boundary  
   - Margins  
   - Support vectors

---

## 📈 Visualization

The model plots:
- The decision boundary separating the two classes
- Margins on either side of the hyperplane
- Support vectors that define the model

![SVM Decision Boundary Plot](#)  
*(Replace with your actual image if you upload one)*

---

## 📊 Output Sample
          precision    recall  f1-score   support

      -1       1.00      1.00      1.00        31  
       1       1.00      1.00      1.00        29  

accuracy                           1.00        60  

---

## ✅ Conclusion

- The SVM model accurately classified customers based on financial indicators.
- The decision boundary and support vectors were successfully visualized.
- This project showcases how SVM can be effectively applied to binary classification problems in the financial domain.

---

## ⚠️ Disclaimer

> This dataset is **synthetically generated** and does not represent real-world bank data. It is intended for **educational and academic use only**.

---

## 📬 Contact

*Built with 💻 by [Sanika Palaw](https://www.linkedin.com/in/sanika-palaw-7583a3289)*  
Feel free to fork, use, and improve!

