# Hyderabad Housing Market Intelligence Dashboard

## 📌 Project Overview

This project is an end-to-end real estate analytics solution built using independently collected market data from a live, JavaScript-rendered real estate platform.

The objective was not just visualization, but to transform raw residential property listings into structured, decision-ready market intelligence for buyers, investors, and analysts.

This project demonstrates:

- Independent web scraping of dynamic websites
- Data cleaning and validation
- Outlier treatment using robust statistics
- Feature engineering
- Exploratory Data Analysis (EDA)
- Dashboard development in Excel and Power BI
- Tool-agnostic analytical consistency

---

## 🎯 Business Problems Addressed

The dashboard was designed to answer practical real estate questions:

- Which localities offer better value for money based on price per square foot?
- How is housing supply distributed across affordability segments?
- How do apartments and villas differ in pricing and value?
- Where are price hotspots within the city?
- How does residential supply differ between city limits and ORR regions?

---

## 📊 Dataset Details

- ~5,000 residential property listings
- City: Hyderabad
- Source: Live JavaScript-rendered real estate platform
- Data collected independently using Selenium

### Key Fields:

- Total Price
- Price per Sqft
- Locality
- Property Type
- Number of Rooms
- Latitude and Longitude
- Listing URL

---

## 🔄 Technical Workflow

Web Scraping (Selenium - JavaScript rendered pages)
↓
Structured Data Extraction
↓
Data Cleaning & Preprocessing
↓
Deduplication using Unique Listing URLs
↓
Outlier Detection & Median-based Metrics
↓
Feature Engineering (Affordability Bands, Locality Grouping)
↓
Exploratory Data Analysis (Pandas / Excel)
↓
Dashboard Creation (Excel & Power BI)



Both dashboards were built independently from the same raw dataset to ensure analytical reproducibility and tool consistency.

---

## 🧹 Data Cleaning & Validation

To ensure reliability and accuracy:

- Removed duplicate listings using unique URL identifiers
- Standardized currency and area formats
- Converted textual price values into numeric format
- Identified and flagged extreme outliers
- Used median instead of mean to reduce skew impact
- Cross-validated aggregates across Excel, Power BI, and Python

---

## 📈 Key Analytical Decisions

### Why Median Instead of Average?

Real estate prices are highly skewed due to luxury listings and extreme high-value properties.

Using median price per sqft ensured:

- Fair comparison across localities
- Reduced distortion from outliers
- Robust comparison across room configurations

---

## 📌 Dashboard Highlights

The dashboard includes:

- Median Price per Sqft by Locality
- Affordability Segmentation (Affordable → Ultra Luxury)
- Property Type Comparison (Apartment vs Villa)
- Geo-based Price Hotspot Identification
- City vs ORR Supply Distribution
- Room-wise Pricing Analysis

---

## 🛠 Tools & Technologies Used

- Python (Pandas)
- Selenium (Web Scraping)
- Excel (Pivot Tables, Advanced Functions)
- Power BI (Interactive Dashboarding)
- Basic Statistical Analysis

---

## 📊 Key Outcomes

- Identified locality-wise pricing disparities
- Segmented the market into investment-friendly affordability bands
- Highlighted premium and emerging residential corridors
- Demonstrated cross-tool analytical consistency

---

## 📚 Learning Outcomes

This project strengthened:

- Real-world web scraping implementation
- Handling messy, unstructured datasets
- Statistical reasoning in skewed distributions
- Building tool-agnostic dashboards
- Converting raw data into actionable business insights

---

## 🔗 Live Dashboard

Power BI Dashboard Link:  
https://app.powerbi.com/links/nbi8-LC9ZW?ctid=56c1d497-700b-49cf-8f8d-3dd6b20d522f&pbi_source=linkShare

---

## 🚀 Future Improvements

- Automated periodic scraping for time-series tracking
- Predictive modeling for price estimation
- Clustering analysis for locality segmentation
- Pipeline automation for data refresh

---

## 👤 Author

**Rakesh Yamjala**  
Data Analyst  
Open to Data Analytics Roles
