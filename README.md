# NYC Green Taxi Data Engineering Project

This project demonstrates how to build a simple **data pipeline** and perform exploratory analysis using the NYC Green Taxi trip dataset.  
It is part of my portfolio for practicing **SQL, Python (pandas), and data engineering concepts**.

👉 [Open in Google Colab](https://colab.research.google.com/drive/1eCTKV5YeUyJjqhZfoUxEJG7FyRoaNA-L?usp=sharing)

---

## 📂 Dataset
- **Source**: [NYC TLC Trip Record Data](https://www.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_green.pdf)  
- **Sample Used**: July 2021 Green Taxi Trips (`green_tripdata_2021-07.csv.gz`)  
- Contains pickup/dropoff times, locations, passenger counts, and trip details.

---

## ⚙️ Pipeline Steps
1. **Extract**: Download raw CSV data directly from the web.  
2. **Transform**:
   - Convert pickup/dropoff timestamps.
   - Calculate trip durations in seconds and minutes.
   - Filter out unrealistic trips (duration <1 min or >2 hours, passenger_count outside 1–6).  
3. **Load**: Store cleaned data into SQLite for analysis.  

---

## 📊 Analysis Questions
1. **Average Trip Duration by Passenger Count**  
   → Do more passengers mean longer or shorter trips?  

2. **Trips by Pickup Hour**  
   → What times of day are the busiest for green taxis?  

3. **Top 10 Pickup Zones by Volume**  
   → Which locations generate the most demand?  

---

## 📈 Visualizations
- Line chart: **Trips by Pickup Hour**  
- Bar chart: **Top 10 Pickup Locations by Trip Volume**  

---

## 🛠️ Tech Stack
- **Python**: pandas, matplotlib  
- **SQL**: SQLite (via SQLAlchemy)  
- **Notebook**: Google Colab / Jupyter  

---

## 🚀 Next Steps
- Automate pipeline with **Airflow**.  
- Store raw and transformed data in a **data warehouse** (e.g., BigQuery, Snowflake).  
- Add dashboards with **Tableau / Power BI**.  

---

## 📧 Contact
If you’d like to connect, reach out on [LinkedIn](https://linkedin.com/in/yourprofile](https://www.linkedin.com/in/jihan-zheng-9a04771bb/).
