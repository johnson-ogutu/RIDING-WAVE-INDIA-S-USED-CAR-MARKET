# 🚗 Riding the Digital Wave: Predicting Used Car Prices in India

### Author: Johnson Ogutu | Data Scientist & Analyst  
📧 ogutujohnson615@gmail.com 
🌐   github link:https://github.com/johnson-ogutu

---

## 💡 Project Summary
This project was developed for a **freelance client in the automotive resale domain** aiming to understand and predict the fair market value of used cars in major Indian cities.  
The goal was to build a **machine learning model** capable of accurately estimating car prices based on attributes such as age, brand, fuel type, and mileage.

---

## 🎯 Objectives
- Build a predictive model to estimate used car prices.  
- Identify the most influential features affecting price variations.  
- Provide actionable insights to help optimize pricing strategy and profit margins.

---

## 📊 Dataset Overview
The dataset represents car listings from various online automobile marketplaces across India.  

| Feature | Description |
|----------|-------------|
| **year** | Year of manufacture |
| **brand** | Car manufacturer |
| **full_model_name** | Detailed model with specs |
| **model_name** | Base model name |
| **price** | Selling price (target variable) |
| **distance_travelled(km)** | Total distance covered |
| **fuel_type** | Type of fuel used |
| **city** | Registration city |
| **car_age** | Age of the car |

---

## 🧠 Approach & Methodology
1. **Data Cleaning & Preparation**
   - Removed duplicates and handled missing values.
   - Converted columns like `year` and `distance_travelled` to numeric formats.

2. **Exploratory Data Analysis (EDA)**
   - Used visualization to explore brand trends and pricing patterns.
   - Studied correlations between mileage, car age, and selling price.

3. **Feature Engineering**
   - Derived `car_age` from the manufacture year.
   - Encoded categorical variables for ML models.

4. **Model Building**
   - Trained multiple models: Linear Regression, Decision Tree, and Random Forest.
   - Selected **Random Forest Regressor** as the final model based on best R² score and lowest RMSE.

5. **Model Evaluation**
   - R² Score: **0.92**  
   - Mean Absolute Error (MAE): **₹42,000**  
   - The model explained **92% of price variance**.

---

## ⚙️ Tech Stack
- **Python 3.10**
- **Pandas, NumPy** – Data Wrangling  
- **Matplotlib, Seaborn** – Data Visualization  
- **Scikit-learn** – Machine Learning  
- **Jupyter Notebook**

---

## 🧾 Deliverables
- **Clean dataset ready for analysis**  
- **Exploratory visualizations**  
- **Trained ML model for car price prediction**  
- **Feature importance insights**  

---

## 🏁 Key Insights
- **Car age** and **distance travelled** have the strongest negative impact on resale price.  
- **Brand** and **fuel type** significantly affect pricing tiers.  
- Random Forest performed best, achieving high accuracy across cities.

---

## 📂 Files in This Repository
| File | Description |
|------|--------------|
| `used_car_price_prediction.ipynb` | Main notebook with full workflow |
| `car_data.csv` | Dataset used for training |
| `README.md` | Project documentation |

---

## 🧭 Future Enhancements
- Deploy as a **Flask web app** for live car price predictions.  
- Integrate with **Streamlit dashboard** for client use.  

---

## 👤 About the Author
**Johnson Ogutu** – Freelance Data Scientist  
Passionate about turning raw data into intelligent business insights.  
📧 ogutujohnson615@gmail.com| 💻 github account:https://github.com/johnson-ogutu
