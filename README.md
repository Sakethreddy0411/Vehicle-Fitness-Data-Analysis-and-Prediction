🚗 Vehicle Fitness Data Analysis & Prediction

📌 Project Overview

This project analyzes vehicle fitness data using a real-world transport dataset.  
It applies data cleaning, exploratory data analysis (EDA), visualization, and machine learning to understand patterns and predict vehicle fitness certificate validity.

🎯 Objectives

* Analyze vehicle fitness status distribution  
* Identify expired and soon-to-expire vehicles  
* Study vehicle class and regional trends  
* Understand the relationship between vehicle age and fitness validity  
* Build a predictive model for validity duration  

📊 Key Insights

* 🚗 Majority of vehicles are in approved fitness status  
* ⏳ Older vehicles tend to have shorter validity periods  
* 🏢 Some offices issue more fitness certificates than others  
* 📈 Fitness certificate trends vary over time  
* 🤖 Model shows relationship between vehicle age and validity  

🛠 Technologies Used

* Python  
* Pandas  
* NumPy  
* Matplotlib  
* Scikit-learn  

📁 Project Structure

Vehicle-Fitness-Analysis/
│
├── analysis.py  
├── dataset.csv  
├── README.md  
├── requirements.txt  

⚙️ Features

✔ Data cleaning and preprocessing  
✔ Date-time conversion  
✔ Exploratory Data Analysis (EDA)  
✔ Visualization (bar charts, line graphs, histogram, scatter plots)  
✔ Feature engineering (vehicle age, validity days)  
✔ Machine Learning model (Linear Regression)  
✔ Prediction of fitness validity  

📈 Visualizations Included

* Vehicle fitness status bar chart  
* Vehicle class vs fitness stacked chart  
* Monthly trend line graph  
* Top offices bar chart  
* Validity distribution histogram  
* Vehicle age vs validity scatter plot with regression line  

🤖 Machine Learning

* Model: Linear Regression  
* Input Feature: Vehicle Age  
* Target Variable: Validity Days  
* Evaluation Metrics:  
  * Mean Absolute Error (MAE)  
  * R² Score  

▶️ How to Run

1. Install required libraries:

pip install -r requirements.txt

2. Run the project:

python analysis.py

📌 Conclusion

This project demonstrates how data analysis and machine learning can be applied to real-world transport data to monitor vehicle fitness and predict certificate validity. It highlights the importance of vehicle age in determining fitness duration.

👨‍💻 Author

**Saketh Reddy Ambati**

🚀 Future Improvements

* Add more features (vehicle type, fuel type)  
* Use advanced models (Random Forest, XGBoost)  
* Build interactive dashboard (Power BI / Streamlit)  
