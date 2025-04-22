# 🚗 Vehicle Emissions Data Analysis

This project analyzes vehicle emissions data to classify vehicles into emission categories based on their CO2 output. It visualizes distributions, compares fuel types, and helps identify trends using Python, Pandas, Seaborn, Matplotlib, and Plotly.

---

## 📁 Dataset

The dataset used in this project contains the following columns:

| Column Name        | Description                                 |
|--------------------|---------------------------------------------|
| `engine_size`      | Engine displacement in liters               |
| `fuel_type`        | Type of fuel used (e.g., petrol, electric)  |
| `co2_emissions`    | CO2 emissions in grams per kilometer        |
| `emission_category`| Existing emission label (e.g., A, B, C...)  |

Sample rows:

```csv
engine_size,fuel_type,co2_emissions,emission_category
1.887888648,petrol,215.4137938,B
1.924299186,electric,234.4639417,C
