# Car Price Prediction 🚗

## 📌 Project Overview
This project aims to predict the selling price of used cars based on several factors such as fuel type, years of service, showroom price, number of previous owners, kilometers driven, seller type, and transmission type. The goal is to build a **Machine Learning (ML) model** that provides an estimated price based on input features.

## 📂 Dataset
- The dataset contains various attributes of cars, including:
  - `Fuel Type`
  - `Years of Service`
  - `Showroom Price`
  - `Previous Owners`
  - `Kilometers Driven`
  - `Seller Type` (Dealer/Individual)
  - `Transmission Type` (Manual/Automatic)

## 🛠️ Technologies Used
- **Python**
- **Pandas** (for data manipulation)
- **NumPy** (for numerical operations)
- **Matplotlib & Seaborn** (for visualization)
- **Scikit-learn** (for ML model)

## 🏗️ Project Workflow
1. **Data Preprocessing**:
   - Handling missing values
   - Encoding categorical variables
   - Feature selection & engineering
2. **Exploratory Data Analysis (EDA)**:
   - Visualizing feature distributions
   - Identifying correlations
3. **Model Selection & Training**:
   - Using **Random Forest Regressor** for price prediction
   - Hyperparameter tuning using `RandomizedSearchCV`
4. **Model Evaluation**:
   - Measuring performance using `RMSE`, `MSE`, and `R² score`
5. **Deployment**:
   - Building a simple **Flask API** (optional)
   - Making predictions for new car entries

## 🚀 How to Run the Project
1. Clone this repository:
   ```bash
    [git clone https://github.com/PradnyaBondarde/ShadowFox.git]
   cd task2
2. Install dependencies:

pip install -r requirements.txt

3. Run the Jupyter Notebook (Car_Price_Prediction.ipynb).
