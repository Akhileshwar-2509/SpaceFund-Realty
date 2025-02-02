# 🚀 Space Fund Realty (SFR) Analysis

## 📌 Project Overview

The **Space Fund Realty (SFR) Analysis** project leverages **Machine Learning, Python, and SQL** to analyze aerospace companies and their missions. The objective is to provide **data-driven insights** for investors, helping them make informed decisions by evaluating companies based on **missions, payload, launch costs, and technological advancements**. 

The **SFR Rating System (1-9)** serves as a **development & stability indicator** for these companies, with higher ratings signifying more established organizations.

---
## 🗂️ Data Dictionary

| Column Name         | Description                                           |
|---------------------|-------------------------------------------------------|
| **Company**         | Name of the aerospace company                         |
| **SFR**             | SpaceFund Realty rating (1-9)                         |
| **Payload(kg)**     | Weight of the payload in kilograms                    |
| **Launch Cost (M USD)** | Cost of the mission launch in million USD     |
| **Price per kg**    | Cost per kg of payload transportation                 |
| **Launch Class**    | Classification of the launch                          |
| **Orbit Altitude**  | Targeted altitude of the orbit                        |
| **Tech Type**       | Type of technology used for the mission               |
| **Country**         | Country of the company's headquarters                 |
| **HQ Location**     | Headquarters location of the company                   |
| **Description**     | Brief description of the mission                       |

---
## 🔍 Insights & Findings

📊 **Geographical Distribution**
- The **USA dominates** the aerospace industry, with the highest number of companies rated **SFR > 6**.
- **China ranks second**, surpassing the UK in high-rated companies.

🚀 **Mission Characteristics**
- Majority of missions are **rocket-based**, classified as **small launch class** and targeted towards **Low Earth Orbit (LEO)**.
- Companies with **higher mission frequencies** have **more stable ratings (SFR > 5)**.

💰 **Launch Cost & Payload Relationship**
- **Higher launch costs and heavier payloads** are positively correlated with **higher SFR ratings**.
- **Well-established companies invest more** in their missions and achieve greater financial stability.

---
## 🧠 Machine Learning Approach

🔹 **Technologies Used**: **Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn), SQL (MySQL for data processing)**

### 📈 Model Implementation
- **Decision Tree Classifier** & **Random Forest Classifier** were trained to **predict SFR ratings**.
- Achieved **87% accuracy** on test data.
- **Feature Importance** analysis highlighted **Launch Cost, Payload, and Orbit Altitude** as the most significant predictors.

📌 **Future Enhancements:**
- Expanding the dataset to **improve recall scores** for predicting SFR > 6.
- Incorporating **Time-Series Forecasting (ARIMA, LSTM)** to analyze industry trends.

---
## 📢 Conclusion

This project provides **valuable insights into the aerospace industry**, helping investors evaluate companies based on mission success, financial stability, and technological advancements. 

By leveraging **Machine Learning & Data Science**, we have developed a **reliable model** to analyze and predict **SpaceFund Realty Ratings**, ultimately aiding **strategic decision-making** in the space exploration sector.

🚀 **Technologies Used**: Python 🐍 | SQL 🗄 | Machine Learning 🤖 | Data Visualization 📊

🔗 **Author**: Akhileshwar Anumula  
🔗 **GitHub**: [Akhileshwar-2509](https://github.com/Akhileshwar-2509)
