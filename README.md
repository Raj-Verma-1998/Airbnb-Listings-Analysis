# 🏠 Airbnb Data Analysis Dashboard

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?style=for-the-badge&logo=powerbi)
![Cities](https://img.shields.io/badge/Cities-Chicago%20%7C%20New%20Orleans-blue?style=for-the-badge)
![Listings](https://img.shields.io/badge/Listings-16%2C070-orange?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=for-the-badge)

> **End-to-end Power BI Dashboard Project** — Analysing 16,070 Airbnb listings across **Chicago** and **New Orleans** to uncover pricing patterns, neighbourhood popularity, host behaviour, and property availability.

---

## 📊 Project Overview

This project uses **Power BI** to build interactive dashboards analyzing Airbnb listings data from two major US cities. Users can explore the data using dynamic filters such as **room type** and **price range**.

| City | Total Listings | Neighbourhoods | Avg Price | Total Reviews |
|------|---------------|----------------|-----------|---------------|
| Chicago | 8,580 | 76 | $107 | ~463K |
| New Orleans | 7,490 | 69 | $260 | ~493K |

---

## 🎯 4 Dashboard Goals

### Goal 1 — Overview Dashboard
- Total listings, neighbourhoods, average price per city
- Top 10 neighbourhoods by listing count
- Most expensive neighbourhoods (Chicago: **Woodlawn** | New Orleans: **Whitney**)

### Goal 2 — Property Analysis
- Availability trends (avg days available per year)
- Minimum nights by room type
- Review activity distribution (High / Moderate / Low / Inactive)

### Goal 3 — Price Analysis
- Price range distribution (Budget / Mid-range / Premium / Luxury)
- Average price by neighbourhood
- Max listing price: **$50,000** in both cities

### Goal 4 — Host Analysis
- Total hosts & avg listings per host
- Review count by host type (Single vs Multi-listing)
- Multi-listing hosts generate the highest engagement

---

## 💡 Key Insights

1. 🏘️ **Entire home/apartment listings dominate** the market in both cities
2. 💰 **Mid-range pricing** contains the majority of listings in both cities
3. 📍 **Popular neighbourhoods** have significantly higher prices and listing counts
4. 👤 **Multi-listing hosts** generate more reviews and higher revenue
5. 🏙️ **Chicago** has more total listings — **New Orleans** has a higher average price ($260 vs $107)
6. 🌙 **Shared rooms** require fewer minimum nights — better for short stays

---

## 🗂️ Project Structure

```
Airbnb-Listings-Analysis/
│
├── Chicago listings.csv          # Raw Chicago Airbnb listings data
├── New Orleans listings.csv      # Raw New Orleans Airbnb listings data
├── Clean_Listings.pbix           # Power BI Dashboard file
├── LICENSE                       # MIT License
└── README.md
```

---

## 📁 Dataset Details

| Column | Description |
|--------|-------------|
| `id` | Unique listing ID |
| `name` | Listing title |
| `neighbourhood` | Neighbourhood name |
| `room_type` | Entire home / Private room / Shared room / Hotel |
| `price` | Price per night ($) |
| `minimum_nights` | Minimum stay requirement |
| `number_of_reviews` | Total reviews received |
| `availability_365` | Days available per year |
| `host_id` | Unique host identifier |

---

## 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| **Power BI Desktop** | Dashboard creation & visualization |
| **Power Query** | Data cleaning & transformation |
| **DAX** | Calculated columns & measures |
| **Excel/CSV** | Raw data source |

---

## 🚀 How to Open

```
1. Download Clean_Listings.pbix
2. Open with Power BI Desktop
3. Use filters (Room Type, Price Range) to explore the dashboard
4. Navigate between 4 dashboard pages
```

> 📥 Download **Power BI Desktop** free from: https://powerbi.microsoft.com/downloads

---

## 📈 Dashboard Pages

| Page | Content |
|------|---------|
| 1️⃣ Overview | City-level summary, top neighbourhoods, room type distribution |
| 2️⃣ Property Analysis | Availability, minimum nights, review activity |
| 3️⃣ Price Analysis | Price ranges, expensive neighbourhoods, pricing patterns |
| 4️⃣ Host Analysis | Host types, listings per host, review engagement |

---

## 👨‍💻 Author

**Raj Verma**
- GitHub: [@Raj-Verma-1998](https://github.com/Raj-Verma-1998)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
