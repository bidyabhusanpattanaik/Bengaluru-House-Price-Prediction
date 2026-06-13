# 🏠 Bengaluru House Price Prediction

A Machine Learning project to predict house prices in Bengaluru 
using Linear Regression and Random Forest algorithms.

## 📊 Dataset
- **Source:** [Kaggle - Bengaluru House Price Data](https://www.kaggle.com/datasets/amitabhajoy/bengaluru-house-price-data)
- **Rows:** 13,320
- **Features:** 9

## 🛠️ Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

## 🔄 Project Workflow

1. Data Loading & Exploration
2. Data Cleaning (Missing values, dtype fixes)
3. Feature Engineering (BHK extraction, price_per_sqft)
4. Outlier Removal (Statistical + Domain knowledge)
5. One-Hot Encoding (Location)
6. Model Building & Comparison
7. Model Evaluation
8. Predictions

## 🤖 Models Compared

| Model              | R² Score | MAE (Lakhs) | RMSE (Lakhs) |
|--------------------|----------|-------------|--------------|
| Linear Regression  | 0.6437   | 26.22       | 75.62        |
| Ridge Regression   | 0.6418   | 26.15       | 75.83        |
| Lasso Regression   | 0.5807   | 29.21       | 82.04        |
| **Random Forest**  | **0.7460** | **21.05** | **63.84**    |

🏆 **Best Model:** Random Forest

## 📈 Sample Predictions

| Location         | Sqft | BHK | Bath | Predicted Price |
|------------------|------|-----|------|-----------------|
| Whitefield       | 1200 | 2   | 2    | ₹ 47.42 Lakhs   |
| Sarjapur Road    | 1500 | 3   | 3    | ₹ 84.81 Lakhs   |
| Electronic City  | 1000 | 2   | 2    | ₹ 29.19 Lakhs   |

## 📁 Project Structure

```
Bengaluru-House-Price-Prediction/
│
├── House_Price_Prediction_BLR.ipynb
├── Bengaluru_House_Data.csv
├── columns.pkl
└── README.md
```

## 🚀 How To Run

1. Clone this repository
   ```
   git clone https://github.com/bidyabhusanpattanaik/Bengaluru-House-Price-Prediction.git
   ```

2. Install required libraries
   ```
   pip install numpy pandas scikit-learn matplotlib seaborn
   ```

3. Open the notebook in Jupyter
   ```
   jupyter notebook House_Price_Prediction_BLR.ipynb
   ```

4. Run all cells

## 📝 Note

The trained model file (`house_price_model.pkl`) is not included 
in this repository due to file size limitations. Running the 
notebook will automatically train and generate the model.

## 👨‍💻 Author
**Bidyabhusan Pattanaik**

⭐ If you like this project, please give it a star!
