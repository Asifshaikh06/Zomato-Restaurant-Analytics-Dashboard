# 🍽️ Zomato Restaurant Analytics Dashboard | Power BI

## 📌 Project Overview

The **Zomato Restaurant Analytics Dashboard** is an interactive business intelligence project developed using Microsoft Power BI. It analyzes restaurant data to generate insights into restaurant distribution, customer engagement, ratings, cuisine preferences, pricing patterns, and market trends.

The dashboard is designed to support two major business perspectives:

- **Customer Perspective:** Helps customers explore restaurants based on location, cuisine, ratings, and pricing.
- **Business Perspective:** Helps restaurant owners and decision-makers understand market presence, customer engagement, cuisine performance, and pricing opportunities.

The project currently includes two analytical dashboard sheets.

---

## 🎯 Business Objectives

- Analyze restaurant distribution across countries and cities.
- Understand customer engagement through restaurant votes and ratings.
- Identify highly rated restaurants and popular cuisines.
- Compare restaurant pricing categories.
- Evaluate cuisine performance across different locations.
- Identify potential market opportunities and areas for business improvement.
- Support data-driven restaurant selection and business decisions.

---

## 📊 Dashboard Sheets

### 1. Restaurant & Customer Intelligence

**Objective:** Provide an overview of restaurant availability, customer engagement, restaurant ratings, and geographical distribution.

**Key KPIs:**
- Total Restaurants
- Total Countries
- Total Cities
- Average Restaurant Rating
- Total Customer Votes
- Average Cost

**Key Visualizations:**
- Restaurant Distribution by Country and City
- Top-Rated Restaurants
- Restaurant Rating Distribution
- Restaurant Distribution by Price Category
- Top Cities by Restaurant Count
- Restaurant Ratings vs Customer Votes
- Restaurant Details and Performance Table

**Business Insights:**
- Identifies countries and cities with the highest restaurant presence.
- Highlights highly rated restaurants.
- Shows customer engagement through voting activity.
- Helps customers compare restaurants based on ratings and pricing.
- Supports geographical market analysis.

### 2. Cuisine, Pricing & Market Intelligence

**Objective:** Analyze cuisine popularity, customer preferences, restaurant pricing, and cuisine performance across markets.

**Key KPIs:**
- Total Cuisines
- Top-Rated Cuisine
- Most Listed Cuisine
- Most Voted Cuisine
- Budget Restaurants
- Premium Restaurants

**Key Visualizations:**
- Top 10 Cuisines by Average Rating
- Top 10 Cuisines by Customer Votes
- Cuisine Distribution by Country and City
- Cuisine Distribution by Price Category
- Average Rating by Price Category
- Restaurant Cost vs Rating Analysis
- Cuisine Rating Distribution

**Business Insights:**
- Identifies cuisines with the strongest restaurant ratings.
- Highlights cuisines receiving the highest customer engagement.
- Compares cuisine availability across geographical markets.
- Analyzes the relationship between pricing and restaurant ratings.
- Helps identify budget-friendly and premium restaurant segments.
- Supports cuisine selection and market opportunity analysis.

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| Microsoft Power BI Desktop | Dashboard development and visualization |
| Power Query | Data cleaning and transformation |
| DAX | Measures, KPIs, and analytical calculations |
| Data Modeling | Fact, dimension, and bridge table relationships |
| Microsoft Excel / CSV | Source data handling |
| GitHub | Project documentation and version control |

---

## 🧩 Data Modeling

The project uses a structured data model to support interactive analysis and filtering.

**Key tables include:**
- `Fact_Resturant` – Main restaurant-level data.
- `Dim_Country_City` – Country and city information.
- `Dim_Cuisine` – Cuisine details.
- `Bridge_Restaurant_Cuisine` – Connects restaurants with multiple cuisines.
- `Dim_Rating` – Restaurant rating categories.

The model supports geographical, cuisine, pricing, and rating-based analysis.

---

## ⚙️ Power BI Features

- Interactive slicers and search functionality.
- Country-to-city drill-down analysis.
- Dynamic KPI calculations.
- Top N restaurant and cuisine analysis.
- Rating and pricing segmentation.
- Cross-filtering between visuals.
- Data modeling using relationships and bridge tables.
- DAX-based business calculations.

---

## 📈 Business Value

This dashboard demonstrates how restaurant data can be transformed into actionable business intelligence.

**For Customers**
- Discover restaurants by location and cuisine.
- Compare ratings and pricing.
- Identify popular and highly rated restaurants.

**For Restaurant Owners**
- Understand customer engagement.
- Evaluate cuisine and pricing performance.
- Compare restaurant presence across markets.
- Identify areas for potential improvement.

**For Business Managers**
- Monitor restaurant distribution.
- Understand market-level trends.
- Support strategic planning and expansion decisions.

---

## 📁 Project Structure

```text
Zomato-Restaurant-Analytics/
│
├── Dashboard/
│   └── Zomato_Restaurant_Analytics.pbix
│
├── Dataset/
│   └── Restaurant_Dataset.csv
│
├── Screenshots/
│   ├── Restaurant_Customer_Intelligence.png
│   └── Cuisine_Pricing_Market_Intelligence.png
│
└── README.md
```

*Update the filenames and folders to match the files you upload to your GitHub repository.*

---

## 🚀 Project Status

**Completed Sheets:**
- [x] Restaurant & Customer Intelligence
- [x] Cuisine, Pricing & Market Intelligence

**Future Enhancements:**
- [ ] Restaurant Business Performance Analysis
- [ ] Advanced market opportunity analysis
- [ ] Additional business insights and recommendations

---

## 👨‍💻 Skills Demonstrated

- Power BI Dashboard Development
- Data Cleaning and Transformation
- Power Query
- DAX Measures and KPI Development
- Data Modeling
- Fact, Dimension and Bridge Tables
- Data Visualization
- Business Intelligence and Analytical Thinking

---

## 📌 Conclusion

The Zomato Restaurant Analytics Dashboard demonstrates practical Business Intelligence skills by converting restaurant data into meaningful insights. The first two sheets focus on restaurant and customer intelligence, followed by cuisine, pricing, and market analysis.

The project showcases the use of Power BI, Power Query, DAX, and data modeling to solve real-world analytical problems and support data-driven decision-making.
