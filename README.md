# 📈 Locally Weighted Regression (LWR)

A machine learning project that implements **Locally Weighted Regression (LWR)** from scratch using Python and NumPy. The model is first demonstrated on a synthetic sine-wave dataset and then applied to the famous **Tips** dataset to predict tip amounts based on the total bill.

## 🚀 Features

- Implementation of Gaussian Kernel from scratch
- Locally Weighted Regression (LWR) without using ML libraries
- Synthetic dataset demonstration
- Real-world dataset (tips.csv) prediction
- Data visualization using Matplotlib
- Adjustable bandwidth parameter (τ)

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib

## 📂 Dataset

**tips.csv**

Required columns:
- `total_bill`
- `tip`

The dataset is commonly available from the Seaborn dataset collection or Kaggle.

## ▶️ How to Run

1. Clone the repository

```bash
git clone https://github.com/stutimahesh/locally-weighted-regression.git
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Place `tips.csv` in the project folder.

4. Run

```bash
python Locally_Weighted_Regression.py
```

## 📊 Output

- Scatter plot of noisy sine-wave data with the fitted LWR curve.
- Scatter plot of Total Bill vs Tip with the LWR regression curve.

## 📚 Concepts Covered

- Lazy Learning
- Non-Parametric Regression
- Gaussian Kernel
- Weighted Least Squares
- Local Regression
