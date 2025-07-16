# 🚦 Task 04: Traffic Violation Data Analysis

This project is part of my Data Science internship, where I analyzed real-world traffic violation data to uncover patterns related to **road conditions**, **weather**, **time of day**, and **location-based hotspots**.

---

## 📊 Objective

To analyze traffic violation data to identify:

- Peak hours and weekdays for violations
- Most common violation types
- Any influence of weather or time on violations
- Accident/violation hotspots on a map

---

## 🗂️ Dataset Used

**Source**: [Montgomery County Open Data Portal](https://data.montgomerycountymd.gov/Public-Safety/Traffic-Violations/4mse-ku6q)  
**File Format**: CSV (No extraction required)  
**Columns Used**:
- `Date Of Stop`
- `Time Of Stop`
- `Violation Type`
- `Weather` *(if available)*
- `Latitude`, `Longitude`

---

## 🛠️ Tools & Libraries

- **Python**
- **Pandas**
- **Matplotlib** & **Seaborn** (for visualizations)
- **Folium** (for interactive maps)

---

## 📌 Key Insights

- Violations mostly occurred between **7 AM – 9 AM** and **4 PM – 6 PM** (rush hours).
- **Friday** recorded the highest number of traffic violations.
- The most frequent violations included **speeding**, **running red lights**, and **failure to obey signs**.
- A heatmap helped locate high-violation areas within Montgomery County.

---

## 📍 Visualizations

- 📈 Bar Charts (Hourly & Weekly patterns)
- 📊 Most common violation types
- 🌍 Heatmap for geographic hotspots

---

## 🚀 How to Run

1. Open [Google Colab](https://colab.research.google.com/)
2. Copy and paste the code from the notebook or open the `.ipynb` file (if uploaded to GitHub)
3. Run all cells to see visualizations and map outputs

---

## 📷 Sample Outputs

![Violations by Hour](sample_outputs/violations_by_hour.png)  
![Heatmap](sample_outputs/heatmap.png)

---

## 👩‍💻 Author

**Shruti Sharma**  
B.Tech CSE (AI & ML) | Chandigarh University  
📫 [LinkedIn](https://www.linkedin.com/in/shruti-sharma/) | 📧 shruti@example.com

---

## 📌 License

This project is for educational purposes only.
