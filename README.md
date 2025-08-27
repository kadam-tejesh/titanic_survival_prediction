# Titanic Survival Prediction using Decision Tree

## 📌 Project Overview  
This project applies **Decision Tree Classification** on the Titanic dataset to predict passenger survival.  
The notebook demonstrates **data preprocessing, feature analysis, and model building** using two different splitting criteria: **Gini Index** and **Entropy**.

---

## ⚙️ Tools & Technologies  
- **Python**  
- **Libraries:** Pandas, Seaborn, Scikit-learn  

---

## 📊 Workflow  
1. **Data Preprocessing**  
   - Handled missing values using forward fill (`ffill`).  
   - Checked and removed duplicates.  
   - Explored feature distributions (e.g., gender).  

2. **Model Building**  
   - Implemented **Decision Tree Classifier** using:  
     - Gini Index  
     - Entropy (Information Gain)  

3. **Model Evaluation**  
   - Compared prediction results for both criteria.  
   - Analyzed classification results (true positives, false negatives, etc.).  

---

## 📈 Results  
- **Decision Tree (Gini Index):**  
  - 84 correct predictions of non-survivors  
  - 55 correct predictions of survivors  
  - 40 misclassified cases  

- **Decision Tree (Entropy):**  
  - 91 correct predictions of non-survivors  
  - 53 correct predictions of survivors  
  - 35 misclassified cases  

🔎 **Entropy-based Decision Tree performed slightly better than Gini.**

---
