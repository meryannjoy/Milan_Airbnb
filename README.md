# Milan Airbnb
A Data Visualization project analyzing how Airbnb listing concentration and typologies redefine housing pressure and inequalities across Milan.

---

## 📌 Project Overview
Short-term rentals have deeply influenced urban affordability and spatial equity in major European cities. This project addresses the following primary research question:

> **"To what extent are the concentration and typology of Airbnb listings redefining housing pressure and inequalities among Milan's neighborhoods?"**

By examining spatial density, room type breakdowns, price-to-activity alignment, host professionalization, and calendar availability across Milan's nine administrative zones (*Municipi*), this study uncovers how the platform transforms long-term residential housing into commercial tourist accommodation.

### 🔍 Key Research Questions
1. **Housing Market Pressure:** Which neighborhoods record the highest density of entire apartments removed from the long-term residential market?
2. **Price vs. Activity Alignment:** How do listing prices align with actual guest activity (reviews) across different urban sectors?
3. **Host Professionalization & Compliance:** To what extent are listings dominated by professional operators (6+ listings), and how does legal compliance vary across host types?
4. **Calendar Availability:** How does annual listing availability differ between host portfolios and urban districts?

---

## 📊 Key Findings
* **Hyper-Localized Core Pressure:** The highest density of entire homes is clustered in the historical center and nightlife hubs (e.g., Duomo at 636.7/km², Ticinese, Navigli, and Buenos Aires - Venezia), dropping sharply toward outer rings.
* **Spatial Mismatch in Activity:** While premium listing prices (≥ €220/night) remain concentrated in the center, guest activity and turnover peak in well-connected transport corridors (Centrale, Loreto, Buenos Aires) at mid-tier pricing.
* **Commercial Domination:** Multi-listing hosts control 64% of all listings (with 6+ listing agencies holding 44.1%), demonstrating that Milan's market is predominantly commercial rather than peer-to-peer home-sharing.
* **Structural Availability:** Median availability sits consistently around 210–227 days/year across all nine districts, showing that properties operate on a permanent, full-time basis across both central and suburban areas.

---

## 🛠️ Tech Stack & Methodology
* **Language & Environment:** Python, Jupyter Notebook
* **Data Processing & Geospatial Analysis:** `pandas`, `geopandas`
* **Data Visualization:** `matplotlib`, `seaborn`, and **Datawrapper** (for interactive choropleth and point mapping)
* **Data Cleaning & Engineering:** Outlier detection, missing-value imputation, spatial joins between listing coordinates and neighborhood boundary polygons, and host portfolio segmentation.

---

## 📂 Data Sources & Limitations
* **Source:** Publicly available listing-level and spatial datasets from [Inside Airbnb](http://insideairbnb.com/).
* **Limitations:**
  * Listing occupancy and turnover are estimated indirectly via reviews (Reviews LTM).
  * License data is self-reported by hosts.
  * Spatial points include intentional privacy displacement (up to ~150m) applied by Airbnb.

