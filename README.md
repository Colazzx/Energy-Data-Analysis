# 📊 Building Energy Consumption Analysis

![Project Image](https://drive.google.com/file/d/1_5sUulGfJ2uiHezTM6B_9z0RUmzK53PY/view?usp=drive_link) <!-- You can upload an image (e.g., a sample plot from your notebook) to make your README more appealing -->

## 📝 Project Overview

This project analyzes building energy consumption across different regions and building types using Python. It covers:
- Data preprocessing (handling missing values, detecting and handling outliers).
- Exploratory data analysis (energy consumption patterns by province, building type, and temperature).
- Visualizations to help understand key trends and correlations in energy consumption.
- Recommendations for energy efficiency improvements as part of ABC's Green Future Initiative.

## 📁 Project Structure
## 🚀 Technologies Used
- **Python 3**
- **Pandas**: For data manipulation
- **Matplotlib & Seaborn**: For data visualization
- **Numpy**: For numerical calculations

## 🔍 Exploratory Data Analysis (EDA)
### Key Questions Answered:
1. **Which province has the highest energy consumption on average?**
   - **East Java (Jawa Timur)** has the highest average energy consumption due to its large industrial base and population.

2. **What is the energy consumption per square meter for different building types?**
   - **Commercial buildings** have the highest energy consumption per sqm, while **residential buildings** have the lowest.

3. **What is the correlation between average temperature and energy consumption?**
   - There is a **negative correlation** (-0.66), indicating that as temperature increases, energy consumption tends to decrease.

## 📈 Visualizations
Here are some of the visualizations from the analysis:

- **Energy Consumption per Floor Area by Region and Building Type**:
  ![Heatmap](https://drive.google.com/file/d/1pTUcFnKci9YtVrJyt3RJzcJwH-Z6EoY8/view?usp=sharing)

- **Correlation between Floor Area, Occupancy Rates, and Energy Consumption**:
  ![Correlation Matrix](https://drive.google.com/file/d/1g-1nPMx_l4SXADv0Xpg8NrWfEs7o5XpD/view?usp=sharing)

- **Energy Consumption Trends by Region and Building Type Over Time**:
  ![Energy Consumption Trends](https://drive.google.com/file/d/1WzLlvGVlJE2zbpn8quDvcfzhK8b4bhD9/view?usp=sharing)

## 🛠️ Data Preprocessing
The data preprocessing steps include:
- **Handling missing values**: Used the median to fill missing occupancy rates.
- **Cleaning columns**: Converted temperatures from Fahrenheit to Celsius and removed units for numerical analysis.
- **Outlier detection and handling**: Applied the IQR method to cap extreme values in several columns.

## 🌱 Green Future Initiative Recommendations
Based on the analysis, recommendations for improving energy efficiency include:
- **Focusing on suburban commercial buildings**, which have the highest energy consumption per sqm.
- **Prioritizing energy upgrades** in rural residential areas where energy consumption is disproportionately high.

## 🤔 Challenges Faced
- **Handling uncleaned data**: The "Average Temperature" column required extensive cleaning due to mixed units and symbols.
- **Outlier detection**: Determining how to treat outliers without losing important data.
- **Complex analysis**: Relating the data to real-world implications for energy management in different building types.

## 📊 Results
The results show significant variations in energy consumption by region, building type, and temperature, with clear patterns emerging that help guide ABC's energy efficiency initiatives.

## 🤝 Contributing
Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/your-username/your-repository/issues).

## 📧 Contact
For any inquiries, please contact:
- **Name**: Caleb Effendi
- **Email**: calebeffendi.work@gmail.com

---

⭐️ If you found this project helpful, give it a star!

