# 🧠 K-Nearest Neighbors (KNN) - Bank Authentication Model

This project implements a machine learning model using the **K-Nearest Neighbors (KNN)** algorithm to classify **banknotes as authentic or fake** based on statistical features extracted from their digital images.

---

## 📂 Dataset: `Bank_Authentication.csv`

The dataset contains **numerical features** derived from wavelet-transformed images of banknotes. It includes:

- `Variance`: Measure of the distribution spread.
- `Skewness`: Asymmetry of the data distribution.
- `Curtosis`: Peakedness of the distribution.
- `Entropy`: Randomness or disorder in the data.
- `Class`: Target label (1 = Authentic, 0 = Fake)

---

## 📌 Project Goals

✅ Build a KNN classifier to detect authenticity of banknotes  
✅ Achieve **over 90% test accuracy**  
✅ Tune the model for best performance  
✅ Visualize training and testing accuracy vs `k`  
✅ Save model for future predictions

---

## 🔧 Technologies Used

- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib / Seaborn
- Jupyter Notebook

---

## 🧪 Model Workflow

1. **Load and explore dataset**
2. **Preprocess and scale features**
3. **Split into training and test sets**
4. **Train KNN model with various `k` values**
5. **Evaluate performance (Train vs Test Accuracy)**
6. **Visualize fitting graph**
7. **Save final model for predictions**

---


