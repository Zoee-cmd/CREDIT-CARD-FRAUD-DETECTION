# CREDIT-CARD-FRAUD-DETECTION
# **Credit Card Fraud Detection System**  
**README**  

## **1. Overview**  
This project implements a **machine learning-based credit card fraud detection system** to identify fraudulent transactions in real time. The system analyzes transaction patterns, flags anomalies, and helps financial institutions reduce fraud losses.  

### **Key Features**  
✔ **Real-time fraud detection** using ML models  
✔ **Anomaly detection** (Isolation Forest, Autoencoders)  
✔ **Transaction risk scoring** (0-100 scale)  
✔ **Dashboard for fraud alerts** (Python + Flask/Dash)  
✔ **Dataset:** [Kaggle Credit Card Fraud Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud)  

---

## **2. Installation & Setup**  
### **Prerequisites**  
- Python 3.8+  
- Libraries: `scikit-learn`, `pandas`, `numpy`, `flask`, `imbalanced-learn`  

### **Steps**  
1. Clone the repo:  
   ```bash  
   git clone https://github.com/your-repo/credit-card-fraud-detection.git  
   ```  
2. Install dependencies:  
   ```bash  
   pip install -r requirements.txt  
   ```  
3. Run the Flask app:  
   ```bash  
   python app.py  
   ```  
4. Access the dashboard at:  
   ```  
   http://localhost:5000  
   ```  

---

## **3. Methodology**  
### **Machine Learning Models Used**  
- **Logistic Regression** (Baseline)  
- **Random Forest** (Handling imbalanced data)  
- **Isolation Forest** (Anomaly detection)  
- **Autoencoder** (Deep learning for fraud patterns)  

### **Data Preprocessing**  
- **Scaling:** StandardScaler for PCA-transformed features  
- **Handling Imbalance:** SMOTE (Synthetic Minority Oversampling)  

### **Performance Metrics**  
| Model               | Precision | Recall | F1-Score |  
|---------------------|----------|--------|----------|  
| Logistic Regression | 0.92     | 0.78   | 0.84     |  
| Random Forest       | 0.96     | 0.85   | 0.90     |  
| Isolation Forest    | 0.94     | 0.82   | 0.87     |  

---

## **4. Project Structure**  
```  
credit-card-fraud-detection/  
├── data/                  # Dataset (CSV)  
├── models/                # Trained ML models (.pkl)  
├── notebooks/             # Jupyter notebooks for EDA & training  
├── app.py                 # Flask web app  
├── requirements.txt       # Python dependencies  
└── README.md  
```  

---

## **5. Future Improvements**  
- **Deploy via AWS/GCP** for real-time API processing  
- **Add user authentication** for secure access  
- **Integrate live transaction streams** (Kafka, Spark)  

---

## **6. Contributors**  
- Team member 1: Anesu Zoe
  -Team member 2: Jelson Manzou  

**License:** MIT  



