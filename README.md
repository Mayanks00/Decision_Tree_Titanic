# 🚢 Decision_Tree_Titanic_Project

## 📄 Internship Project Details
**PROJECT_NAME** : Decision_Tree_Titanic_Project  
**COMPANY** : CODETECH IT SOLUTIONS  
**NAME** : MAYANK PRATAP SINGH  
**INTERN_ID** : CT04DH1775  
**DOMAIN** : MACHINE LEARNING  
**DURATION** : 4 WEEKS  
**MENTOR** : Neela Santhosh Kumar  



## 📌 Project Overview

This project demonstrates the **implementation of a Decision Tree Classifier** using **Python and Scikit-learn** to predict **Titanic passenger survival**.  

The project covers the **entire ML workflow**:  

1. **Data Preprocessing & Cleaning** 🧹  
2. **Model Training using Decision Tree** 🌳  
3. **Visualization of the Tree & Model Rules** 🎨  
4. **Manual & Batch Predictions** 🎯  
5. **Model Saving & Export to JSON / PKL** 💾  
6. **Prediction Results Exported to CSV** 📄  

This project is designed to **showcase model interpretability and real-world prediction workflow** for machine learning beginners and practitioners.



## ⚙️ Tech Stack Used

- **Python** 🐍  
- **Google Colab / Jupyter Notebook**  
- **Libraries:**
  - `pandas` – Data manipulation  
  - `numpy` – Numerical operations  
  - `matplotlib` & `seaborn` – Visualization  
  - `scikit-learn` – Model building  
  - `graphviz` & `pydotplus` – Decision tree visualization  
  - `joblib` & `json` – Model serialization  


## 📊 Dataset Information

The **Titanic dataset** is used to classify passengers into **Survived (1) or Not Survived (0)** based on:  

- Passenger Class (`pclass`)  
- Gender (`sex`)  
- Age (`age`)  
- Siblings/Spouse (`sibsp`)  
- Parents/Children (`parch`)  
- Fare (`fare`)  
- Embarkation Port (`embarked`)  

**Source:** [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data)


## 🔑 Key Features of the Project

- ✅ **Decision Tree Model** trained with Titanic data  
- ✅ **Model Visualization** with Matplotlib & Graphviz  
- ✅ **Model Export** in `.pkl` & `.json` formats  
- ✅ **Batch Predictions** for multiple passengers  
- ✅ **Prediction Results Exported to CSV**  
- ✅ **Well-Structured GitHub Project** for portfolio showcase  



## 📂 Project Structure

Decision_Tree_Titanic_Project/

│
├── notebook/

│ └── Titanic_Decision_Tree.ipynb # Colab notebook with all steps
│
├── model/

│ ├── decision_tree_model.pkl # Saved trained model

│ └── titanic_decision_tree.json # Decision tree rules in JSON
│
├── visuals/

│ └── titanic_decision_tree.png # Decision tree visualization

│
├── data/

│ └── titanic.csv # Dataset used

│
├── results/

│ └── predictions_sample.csv # Batch prediction results

│
├── README.md # Project documentation

├── requirements.txt # Libraries required

└── .gitignore # Ignored files



## 📸 Sample Outputs

**1️⃣ Decision Tree Visualization**

![Decision Tree](visuals/titanic_decision_tree.png)

**2️⃣ Sample Batch Predictions**

| pclass | sex | age | sibsp | parch | fare  | embarked | Prediction | Result        |
|--------|-----|-----|-------|-------|-------|---------|-----------|---------------|
| 3      | 0   | 22  | 1     | 0     | 7.25  | 2       | 0         | Not Survived  |
| 1      | 1   | 38  | 1     | 0     | 71.28 | 0       | 1         | Survived      |



## 🚀 How to Run the Project-


 Clone the Repository-


   git clone https://github.com/Mayanks00/Decision_Tree_Titanic_Project.git
   cd Decision_Tree_Titanic_Project

Install Dependencies-

pip install -r requirements.txt

Open the Notebook-

Run Titanic_Decision_Tree.ipynb in Colab or Jupyter Notebook

Generate Predictions-

Modify the input features in the notebook for manual or batch prediction

📬 Contact-
MAYANK PRATAP SINGH
📧 mayankpratapsingh761@gmail.com







