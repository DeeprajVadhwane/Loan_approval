# 🏦 Loan Price Prediction — ML Deployment using Hugging Face Spaces

This project demonstrates how to build, package, and deploy a complete **Machine Learning Loan Approval Prediction System** using **Streamlit** and **Hugging Face Spaces**.

The system predicts whether a customer's loan request should be **Approved** or **Rejected**, based on multiple financial and demographic factors.

---

## 🚀 Project Workflow (ML Pipeline)

### **1️⃣ Data Loading**
- Dataset: `loan_approval_dataset.csv`
- Basic cleaning and column formatting.

### **2️⃣ Feature Engineering**
- Identify **categorical** and **numerical** columns.
- Handle missing values.
- Encode categorical features using **LabelEncoder**.
- Scale numerical values using **MinMaxScaler**.

### **3️⃣ Model Training**
- Algorithm used: **K-Nearest Neighbors (KNN)**
- Test accuracy printed during training.
- Saves all artifacts needed for deployment.

### **4️⃣ Saving ML Artifacts**
The following files are saved and used in production:


These ensure the exact preprocessing steps used during training are applied again during app prediction.

---

## 🧠 Technologies Used

| Component     | Technology                     |
|---------------|--------------------------------|
| ML Model      | K-Nearest Neighbors            |
| Preprocessing | Label Encoding, MinMax Scaling |
| Web App       | Streamlit                      |
| Deployment    | Hugging Face Spaces            |

---

## 🖥 Streamlit Application Features

- Banking-style premium UI  
- Dropdowns for categorical features  
- Numeric inputs for numerical features  
- One-click prediction  
- Beautiful card-based result display  
- Works 100% online on Hugging Face  

---

## 📦 Project Structure

    📁 Loan-Prediction-App
    │── app.py
    │── model.pkl
    │── scaler.pkl
    │── label_encoders.pkl
    │── cat_cols.pkl
    │── num_cols.pkl
    │── feature_order.pkl
    │── requirements.txt
    │── README.md

    
---

## 🌐 Deploying on Hugging Face Spaces

### **Step 1 — Create a New Space**
- Go to HuggingFace → Spaces  
- Select **Streamlit** template  
- Name your space (public/private)

### **Step 2 — Add Your Project Files**
Upload all files:

app.py
model.pkl
scaler.pkl
label_encoders.pkl
cat_cols.pkl
num_cols.pkl
feature_order.pkl
requirements.txt
README.md


### **Step 3 — requirements.txt**

streamlit
pandas
numpy
scikit-learn==1.3.2


### **Step 4 — App Runs Automatically**
Hugging Face will:
- Install dependencies  
- Launch Streamlit  
- Initialize your app  


➡ Just wait — dependencies are still installing.

---

## ✅ Final Output

The deployed app predicts:

### ✔ **Approved**  
or  
### ❌ **Rejected**

Based on customer data processed through your ML pipeline.

---

## ❤️ Developed By  
**Deepraj**  
Data Scientist | Content Creator | Data Analyst




