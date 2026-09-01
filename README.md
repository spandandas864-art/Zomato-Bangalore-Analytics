# Zomato Bangalore Business Analytics & Strategy

An end-to-end data analytics and business intelligence project analyzing **51,205 restaurant listings** across Bangalore to evaluate platform supply dynamics, pricing tier distributions, customer engagement metrics, and expansion opportunities.

---

## Business Problem & Context

Bangalore’s food services industry is one of the most dynamic and hyper-competitive urban markets in South Asia. For food delivery platforms like Zomato, as well as restaurant operators and cloud kitchen investors, success depends on balancing market supply, customer satisfaction, and pricing efficiency across distinct neighborhoods.

### The Core Challenges
1. **Unbalanced Merchant Supply:** High-density commercial and student hubs (such as BTM Layout and Koramangala) face intense merchant competition, whereas emerging residential zones experience coverage gaps.
2. **Platform Monetization & Feature Adoption:** While online ordering is widely adopted, high-margin offerings like **Table Booking** (12.5% adoption rate) remain heavily underutilized, missing key revenue opportunities in higher-priced dining segments.
3. **Rating Disparities & Merchant Churn:** A significant portion of platform listings suffer from low review volume and below-average rating distributions, impacting customer retention and ordering conversion.
4. **Cuisine & Portfolio Optimization:** Restaurant partners frequently struggle to optimize menu offerings and price points relative to localized neighborhood purchasing power (median cost for two: **₹400**).

---

## Project Overview & Interactive Dashboard

This analysis extracts actionable intelligence from restaurant attributes, geographical concentrations, user engagement metrics, and pricing structures to solve these supply-side challenges.

* **Interactive Tableau Dashboard:** [https://public.tableau.com/views/ZomatoBangaloreAnalytics/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link]*
* **Full Executive Report:** See `reports/business_recommendations.md`

---

## Key Findings

* **Market Composition:** **Quick Bites** (37.9% / 19,386 listings) and **Delivery** (50.2% / 25,695 listings) form the backbone of platform supply. The platform average cost for two is **₹555.17** (median: **₹400.00**).
* **Geographic Density:** Platform listings cluster heavily in primary commercial hubs led by **BTM Layout** (5,078 location listings / 3,252 city listings).
* **Feature Adoption:**
  * **Online Ordering:** 59.2% overall adoption rate.
  * **Table Booking:** Restricted primarily to premium segments with a platform-wide adoption rate of just 12.5%.
* **Quality Benchmarks:** Ratings average **2.99 / 5.00** across all listings, with active, high-volume restaurants clustering between **3.60** (50th percentile) and **3.90** (75th percentile).

---

## Strategic Recommendations

1. **Optimize Delivery Logistics in High-Density Hubs:** Concentrate fleet management in BTM Layout and Koramangala while onboarding the 40.8% of non-online merchants to maximize platform Gross Merchandise Value (GMV).
2. **Monetize Table Booking:** Expand targeted reservation software sales to Casual Dining, Pubs, and Bars where cost-for-two reaches up to ₹2,000.
3. **Promote Multi-Cuisine Cloud Kitchens:** Encourage cloud kitchen operators to bundle complementary high-volume cuisines (North Indian, Chinese, Fast Food) to increase order values.
4. **Merchant Quality & Rating Enablement:** Implement targeted review collection tools for low-engagement merchants to help elevate platform ratings toward the 3.6–3.9 quality benchmark.

---

## Repository Structure

```text
├── src/
│   └── zomato_data_analysis.py       # Data extraction, cleaning, and exploratory data analysis
├── reports/
│   └── business_recommendations.md   # Executive summary and detailed recommendations
├── README.md                         # Project documentation and business problem breakdown
└── .gitignore                        # Git ignore file
