# Eda-project
# 🚗 Vehicle Sales Data Analysis

## 📘 Project Description
This project analyzes a **dirty dataset** of vehicle sales to uncover the key factors influencing selling prices. The Jupyter Notebook demonstrates **data cleaning**, **feature exploration**, and **visual analysis** to understand how various vehicle attributes affect resale value.

## ⚙️ Setup Instructions
To run this project locally, follow these steps:

1. **Clone the repository**
   ```bash
   git clone <repository_url>
Navigate to the project directory

bash
Copy code
cd <repository_name>
Install dependencies
It’s recommended to use a virtual environment.

bash
Copy code
pip install pandas numpy matplotlib seaborn
Ensure the data file is available
Place the dataset vehicle_sales_dirty.csv in the project directory.

Run the Jupyter Notebook

bash
Copy code
jupyter notebook vehicle_sales_analysis.ipynb
📊 Analysis Summary
The analysis revealed several key insights regarding factors that influence a vehicle’s selling price:

🔹 Overall
Selling price is mainly influenced by present price, model year, engine size, and kilometers driven.
Premium brands, diesel cars, and automatic transmissions generally have higher resale values.
Older vehicles and high-mileage cars depreciate faster.

🔹 Brand vs. Price
Premium brands such as BMW, Audi, and Mercedes show higher average selling prices compared to budget-oriented brands.

🔹 Present vs. Selling Price
A strong positive correlation exists between the present price (original price) and the selling price — more expensive cars retain greater resale value.

🔹 Driven Kilometers
Selling price decreases with higher kilometers driven, reflecting depreciation with use.

🔹 Engine Capacity
Cars with larger engine sizes (CC) tend to have higher selling prices.

🔹 Mileage (kmpl)
Vehicles with higher mileage (fuel efficiency) often have lower selling prices, as they typically represent smaller, more economical models.

🔹 Fuel Type
Diesel cars command higher selling prices than petrol, electric, or hybrid vehicles.

🔹 Transmission
Automatic transmissions generally result in higher resale values compared to manual ones.

🔹 Selling Price Distribution
The majority of cars fall within the lower price range, with a smaller number of high-end luxury cars.

🔹 Model Year
Newer vehicles have significantly higher resale values, showing the impact of age on depreciation.

🔹 Correlation Heatmap
The heatmap confirms:

Strong positive correlation: Selling price ↔ Present price, Engine size, Model year

Negative correlation: Selling price ↔ Driven kilometers

🧾 Data Source
The dataset used in this project is a publicly available "dirty" dataset of vehicle sales, requiring substantial cleaning and preprocessing before analysis.

🤝 Contributing
Contributions are welcome!
If you’d like to improve this project:

Fork the repository

Create a feature branch (git checkout -b feature-name)

Commit your changes

Push to your branch and open a Pull Request

📈 Example Visuals (Optional)
(You can add sample plots here if available — such as correlation heatmap, price distribution, or brand comparison charts.)

🧠 Author
Developed as part of a data analysis and visualization exercise to explore relationships between vehicle attributes and resale value.

⭐ If you find this project useful, don’t forget to star the repository!

yaml
Copy code

---

Would you like me to make it more **data-science portfolio–friendly** (e.g., with badges, sections for motivation,
