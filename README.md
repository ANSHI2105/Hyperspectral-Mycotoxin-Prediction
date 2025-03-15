# Hyperspectral-Mycotoxin-Prediction

## 📖 Project Overview
This project applies **Machine Learning and Dimensionality Reduction** techniques to predict **mycotoxin (DON) levels** in corn samples using **hyperspectral imaging data**.

### **🔍 Key Tasks:**
- **Preprocessing:** Handling missing values, normalizing features, and visualizing spectral bands.
- **Dimensionality Reduction:** Implementing **PCA** to reduce feature dimensions and analyzing variance explained.
- **Model Training:** Using **Random Forest & XGBoost**, optimizing hyperparameters, and evaluating performance.
- **Model Evaluation:** Computing **MAE, RMSE, R²**, and generating actual vs. predicted value plots.

---

## ⚙️ Installation & Dependencies
### **Dependencies (Python 3.8+)**
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `xgboost`

### **If using Jupyter Notebook:**
```bash
pip install notebook
jupyter notebook
```

---

## 📂 Repository Structure
```plaintext
📦 Hyperspectral-Mycotoxin-Prediction
 ┣ 📂 data/                          # Contains dataset
 ┣ 📂 src/                           # Source code directory
 ┃ ┣ 📜 preprocess.py                # Data preprocessing & cleaning
 ┃ ┣ 📜 dimensionality_reduction.py  # PCA implementation
 ┃ ┣ 📜 train_model.py               # Model training & evaluation
 ┣ 📂 notebooks/                     # Jupyter Notebooks for analysis
 ┣ 📜 ImagoAI.ipynb                  # Main Jupyter Notebook (Google Colab version)
 ┣ 📜 report.pdf                     # Project Report (Preprocessing, PCA, Model Insights)
 ┣ 📜 README.md                      # Project documentation (this file)
 ┣ 📜 requirements.txt               # Required dependencies
```

---

## 🚀 Usage Instructions
```bash
# 1️⃣ Run Data Preprocessing
python src/preprocess.py

# 2️⃣ Apply PCA & Visualize Results
python src/dimensionality_reduction.py

# 3️⃣ Train Models & Evaluate Performance
python src/train_model.py
```

For Jupyter Notebook users, open `ImagoAI.ipynb` in **Google Colab** or **Jupyter Notebook**.
