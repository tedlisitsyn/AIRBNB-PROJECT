# 🏙️ Seattle Airbnb Data Analysis: Planning the Perfect Trip for 6 Friends

This project investigates Airbnb data in Seattle to help plan an affordable, comfortable, and convenient vacation for a group of 6 friends. By combining open data with Python tools, we explored the best time to travel, how to filter trustworthy listings, and how to find the optimal accommodation setup.

---

## 💡 Motivation

Planning group trips is often difficult due to trade-offs between cost, quality, and location. Our goal was to eliminate guesswork using data — helping identify:

- The best **month** to visit Seattle  
- The most reliable **Airbnb ratings**  
- The optimal type and number of listings for **6 people under $1500**, all within walking distance

---

## 🧰 Libraries Used

- `pandas` — data loading and manipulation  
- `matplotlib` — charts and visualizations  
- `folium` — interactive maps of selected listings  

---

## 📁 Repository Contents

| File                                | Description |
|-------------------------------------|-------------|
| `calendar.csv`                      | Daily availability and prices of listings |
| `listings.csv`                      | Main dataset with all Airbnb listing metadata |
| `reviews.csv`                       | User reviews and ratings for each listing |
| `AIRBNB Seattle Investigation.html` | Interactive HTML report with full analysis, visualizations, and maps |
| `AIRBNB Seattle Investigation.ipynb`| Jupyter Notebook version of the analysis for interactive exploration |
| `README.md`                         | This file — documentation of the project |

---

## 📊 Summary of Analysis

- ✅ **Best month to visit**: **March**  
  Balanced across affordability, availability, weather, and low rainfall.

- 🛏️ **Best room type**: "Entire home/apartment"  
  It’s the most common and group-friendly option in Seattle.

- ⭐ **Ratings to trust**: 94–98  
  Most listings fall here. Perfect 100s were excluded as potentially fake.

- 👯 **Perfect setup for 6 friends**:  
  We identified a cluster of listings that:
  - Host exactly 6 guests  
  - Are within 2 miles of each other  
  - Stay under $1500 total for 3 nights  
  - Are all well-rated and available in March

---

## 📝 Read the Full Story

Check out the Medium version of this project for visuals, commentary, and travel insights:  
👉 [Read on Medium](https://medium.com/@tedlisitsyn/what-if-your-next-group-trip-wasnt-just-fun-but-also-data-optimized-6782d4aff7e6)
