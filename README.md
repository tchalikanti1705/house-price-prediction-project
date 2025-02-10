# House Price Prediction Model

## 📌 Overview
This project is about predicting house prices using a **Linear Regression Model built from scratch**. We will not use external ML libraries like Scikit-Learn. Instead, we will implement everything using just **NumPy and Pandas**. This project is great for beginners to understand how Machine Learning models work under the hood.

---

## 📂 Project Structure
This project follows a clean and structured format:

```
house-price-prediction/
│── data/                  # 📂 Stores dataset files
│   ├── housing.csv        # 📄 House price dataset
│
│── src/                   # 📂 Source code
│   ├── data_preprocessing.py  # 📄 Loads and cleans dataset
│   ├── linear_regression.py    # 📄 Implements Linear Regression from scratch
│   ├── train.py           # 📄 Trains the model
│   ├── evaluate.py        # 📄 Evaluates model performance
│
│── notebooks/             # 📂 Jupyter Notebooks (Optional for data exploration)
│   ├── exploratory_analysis.ipynb  # 📄 Analyzes the dataset
│
│── README.md              # 📄 Project explanation and setup guide
│── requirements.txt       # 📄 Required dependencies (Minimal: NumPy, Pandas)
│── .gitignore             # 📄 Ignore unnecessary files (e.g., logs, system files)
```

---

## 📄 Explanation of Each Folder & File

### **1️⃣ Data Folder (`data/`)**
- Stores the dataset files.
- `housing.csv` contains the house price dataset.

### **2️⃣ Source Code (`src/`)**
- `data_preprocessing.py` → Loads and cleans the dataset.
- `linear_regression.py` → Implements **Linear Regression from scratch**.
- `train.py` → Trains the model on the dataset.
- `evaluate.py` → Tests the model and calculates accuracy.

### **3️⃣ Notebooks (`notebooks/`)**
- Contains **Jupyter Notebooks** for analyzing data.
- `exploratory_analysis.ipynb` → A simple analysis of the dataset before training.

### **4️⃣ Main Files**
- `README.md` → **You are reading it now!** Explains the project and how to use it.
- `requirements.txt` → **Lists required dependencies** like NumPy & Pandas.
- `.gitignore` → **Excludes unnecessary files** (logs, system files, etc.).

---

## 🚀 How to Use This Project

### **Step 1: Clone the Repository**
```bash
git clone https://github.com/yourusername/house-price-prediction.git
cd house-price-prediction
```

### **Step 2: Install Dependencies**
```bash
pip install -r requirements.txt
```

### **Step 3: Run the Code**
#### 1️⃣ Load & Preprocess Data
```bash
python src/data_preprocessing.py
```
#### 2️⃣ Train the Model
```bash
python src/train.py
```
#### 3️⃣ Evaluate Model
```bash
python src/evaluate.py
```
