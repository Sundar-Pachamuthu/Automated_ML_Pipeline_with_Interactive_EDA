# 🧠 Automated ML Pipeline with Interactive EDA  

This project is a **Machine Learning Automation Pipeline** built in Python.  
It allows users to upload datasets in multiple formats (CSV, Excel, JSON, XML, SQL) and automatically performs **EDA, preprocessing, and ML model training** — without requiring any manual coding.  

---

## ✨ Features
- 📂 **Flexible Input**: Accepts datasets in CSV, Excel, JSON, XML, and SQL.  
- 🔍 **Automated EDA**:  
  - Detects null values and allows the user to choose between **drop** or **fill** (with median/mode).  
  - Detects and handles multicollinearity.  
- 🏷️ **Task Type Detection**: Automatically identifies **Classification** or **Regression**.  
- ⚙️ **Preprocessing Variants**:  
  1. Raw data  
  2. Log-transformed + Outlier removal  
  3. PCA-transformed  
  4. PCA with variance percentage  
- 🤖 **Model Selection & Tuning**: Runs multiple ML algorithms with hyperparameter tuning.  
- 📊 **Performance Comparison**: Selects the best-performing model using evaluation metrics.  

---

## 🛠️ Tech Stack
- **Python 3.11+**  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  
- TensorFlow / Keras  

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/Sundar-Pachamuthu/Automated_ML_Pipeline_with_Interactive_EDA/.git
   cd MLProjectSample
   
2. Install dependencies:
   ```bash
   pip install -r requirements.txt

3. Run the notebook:
   ```bash
   jupyter notebook Automated_ML_Pipeline_with_Interactive_EDA.ipynb

---

## 📊 Workflow  

- 📂 **Load dataset** (CSV, Excel, JSON, XML, SQL).  
- 🔍 **Automated EDA**: null handling, multicollinearity check.  
- 🏷 **Task type detection**: Regression vs Classification.  
- ⚙ **Preprocessing**:  
  - Raw data  
  - Log + Outlier removal  
  - PCA  
  - PCA (variance-based)  
- 🤖 **Model training & hyperparameter tuning**.  
- 🏆 **Best model selection** with evaluation metrics.  

---

## 👨‍💻 Author  

**Sundar Pachamuthu**  
📧 sundarkarthick574@gmail.com    
🌐 https://github.com/Sundar-Pachamuthu
