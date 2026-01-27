# 🏦 Bank Note Authentication using Random Forest

This project focuses on detecting whether a bank note is **authentic or forged** using machine learning techniques.  
A **Random Forest Classifier** is used to build an accurate and reliable prediction model.

---

## 📂 Project Structure

bank_note_random_forest.ipynb # Jupyter Notebook with full implementation
data_banknote_authentication.csv # Dataset used for training and testing
README.md # Project documentation
---

## 📊 Dataset Description

The dataset contains features extracted from images of bank notes using **wavelet transforms**.

**File:** `data_banknote_authentication.csv`

### Columns:
| Feature | Description |
|-------|-------------|
| variance | Variance of wavelet transformed image |
| skewness | Skewness of wavelet transformed image |
| curtosis | Curtosis of wavelet transformed image |
| entropy | Entropy of image |
| class | Target variable (0 = Fake, 1 = Authentic) |

---

## ⚙️ Technologies Used

- Python  
- Jupyter Notebook  
- NumPy  
- Pandas  
- Matplotlib / Seaborn  
- Scikit-learn  

---

## 🧠 Machine Learning Model

- **Algorithm:** Random Forest Classifier  
- **Type:** Supervised Learning (Classification)  

### Steps Performed:
1. Data loading and exploration  
2. Data preprocessing  
3. Train-test split  
4. Model training using Random Forest  
5. Model evaluation (Accuracy, Confusion Matrix, etc.)

---

## 📈 Model Evaluation

The model is evaluated using:
- Accuracy Score  
- Confusion Matrix  
- Classification Report  

Random Forest performs well due to its ability to handle non-linear data and reduce overfitting.

---

## ▶️ How to Run the Project

1. Clone the repository or download the files
2. Install required libraries:
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn


