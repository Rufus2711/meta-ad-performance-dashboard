# Meta Ad Performance Dashboard

## Project Overview

This project is an interactive Power BI dashboard built to analyze Meta (Facebook & Instagram) ad campaign performance across multiple KPIs including impressions, clicks, engagement, conversions, and purchases.

The dashboard provides insights into:
- Audience engagement behavior
- Campaign effectiveness
- Platform performance
- Ad-type performance
- Geographic trends
- Time-based activity patterns

---

## Business Objective

The goal of this project is to evaluate advertising performance and identify opportunities to improve:
- Engagement
- Conversion efficiency
- Audience targeting
- Budget allocation
- Campaign scheduling

---

## Tools & Technologies Used

- Power BI
- DAX
- Field Parameters
- Data Modeling
- Interactive Visualizations

---

## Data Model

The dashboard follows a star schema design:

### Fact Table
- `ad_events`

### Dimension Tables
- `ads`
- `campaigns`
- `users`

---

## Key KPIs

- Impressions
- Clicks
- Shares
- Comments
- Purchases
- CTR (Click Through Rate)
- Engagement Rate
- Conversion Rate
- Purchase Rate
- Total Budget
- Average Budget per Campaign

---

## Dashboard Features

- Dynamic KPI switching using Field Parameters
- Dynamic visual titles
- Audience segmentation analysis
- Hourly engagement trend analysis
- Weekly trend analysis
- Geographic performance analysis
- Ad-type comparison matrix
- Platform-level filtering
- Interactive slicers and cross-filtering

---

## Key Insights

- Strong awareness and engagement performance
- Conversion efficiency drops significantly lower in the funnel
- Female users show higher engagement compared to males
- Video and Story ads perform better than Image and Carousel ads
- Afternoon and evening hours generate stronger engagement
- India and Brazil drive high engagement volume

---

## Recommendations

- Increase investment in Video and Story ad formats
- Improve landing page and conversion funnel experience
- Focus retargeting efforts on engaged users
- Schedule campaigns during peak engagement hours
- Build region-specific campaign strategies

---

## Repository Structure

```text
meta-ad-performance-dashboard/
│
├── dashboard/
│   └── Meta_Ad_Performance_Dashboard.pbix
│
├── datasets/
│   ├── ad_events.csv
│   ├── ads.csv
│   ├── campaigns.csv
│   └── users.csv
│
├── dax/
│
└── README.md
```

---

## Skills Demonstrated

### Power BI
- Dashboard Design
- DAX Measures
- Field Parameters
- Data Modeling
- Interactive Reporting

### Analytics
- KPI Analysis
- Funnel Analysis
- Audience Segmentation
- Geographic Analysis
- Campaign Performance Analysis
