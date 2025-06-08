# 🚖 Uber Trip Analysis Dashboard (Power BI)

This project presents an interactive **Power BI dashboard** built to analyze Uber ride data for June 2024. It provides deep insights into trip timing, fare metrics, vehicle usage, and location-based trends. The dashboard enables stakeholders to explore ride patterns, peak hours, and customer preferences in a highly visual and intuitive format.

---

## 📊 Dashboard Pages

### 1️⃣ Overview Analysis

- Total bookings and revenue KPIs  
- Trip breakdowns by payment type, vehicle, and time of day  
- Most frequent pickup and drop-off points  
- Farthest trip and location-based summaries

![Overview](images/overview.png)

---

### 2️⃣ Time Analysis

- Bookings by pickup hour and day name  
- Heatmap showing ride density by hour and weekday  
- Average booking value and distance over time

![Time Analysis](images/Time Analysis.png)

---

## 📁 Dataset Details

### 📌 Table – `Trip Details`

This table contains granular trip-level data including:

- **Trip ID** – Unique identifier for each Uber ride  
- **Pickup Time** – Date and time when the trip started  
- **Drop Off Time** – Date and time when the trip ended  
- **Passenger Count** – Number of passengers  
- **Trip Distance** – Miles traveled  
- **PULocationID** – Pickup location code  
- **DOLocationID** – Drop-off location code  
- **Payment Type** – Cash, card, wallet, etc.  
- **Fare Amount** – Base fare before additional fees  
- **Surge Fee** – Additional fee during peak demand  
- **Vehicle** – UberX, UberXL, Uber Black, etc.

---

### 📌 Table – `Location Table`

This reference table maps numeric location IDs to meaningful area names:

- **LocationID** – Unique key for each location  
- **Location** – Name of the neighborhood or area  

This mapping enables aggregation and analysis at the area level (pickup/drop-off trends).

---

## 💡 Key Insights

- **Peak usage** observed between 8 AM and 6 PM on weekdays  
- **UberX** dominates the vehicle choice with highest booking share  
- **Penn Station/Madison Sq West** and **Upper East Side North** are the top pickup and drop-off points  
- **Weekend nights** see a rise in longer trips and higher surge fees  

---


---

## 📎 Author

**Chirag Pandey**  
📧 [Your email or portfolio link, optional]

---

Feel free to fork this project, use the dataset, or suggest improvements via pull requests!

