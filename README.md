![Tableau](https://img.shields.io/badge/Tableau-Public-blue)
![Excel](https://img.shields.io/badge/Excel-Data_Analysis-green)
![SQL](https://img.shields.io/badge/SQL-Data_Preparation-lightgrey)
![Data Analysis](https://img.shields.io/badge/Data-Analytics-orange)

# Subscription Growth & Churn Analysis (2020 to 2026)

A Tableau dashboard tracking subscriber growth, churn and retention for 20 subscription providers across streaming, gaming, software and audio, from 2020 to 2026. Built with Tableau, Excel and SQL.

## Project overview

The project follows the subscription market from the 2020 to 2021 surge to the slowdown that came after it. It compares four sectors: streaming, gaming, software (SaaS) and audio.

The dataset was compiled from publicly available industry statistics and market reports, then structured and validated in SQL and exported to the Excel file in this repo as one table: subscribers, active users, churned users, churn rate, retention rate and year-on-year growth for each provider and year.

**About the figures.** Some values are estimated or interpolated to keep the series continuous. Churn and retention rates are held at one value per provider for the whole period, so the dataset compares churn between sectors and providers. It does not show churn changing over time. The figures demonstrate analysis, data modelling and dashboard design, and are not official market statistics.

## Business problem

A subscription business loses revenue quietly when growth slows and churn stays high. A retention manager needs to know which categories are most exposed, where growth has stalled, and where a retention budget will do the most good.

## Key insights

- **Growth slowed every year but one.** Total subscribers across the 20 providers almost doubled, from 1.74 billion in 2020 to 3.43 billion in 2026. Year-on-year growth fell from 19.6% in 2021 to 5.1% in 2026.
- **Streaming has nearly stopped growing.** Its growth fell from 17.7% in 2021 to 1.7% in 2026. Disney+ lost subscribers in each of the last four years, and HBO Max and Hulu both shrank in 2026.
- **Streaming also churns the most.** Churn rates run from 25% to 40% for streaming providers, against 15% for audio, 8% to 17% for gaming and 5% for software.
- **Software is the stable half of the market.** Software subscriptions grew 128% over the period, were still growing 7.4% in 2026, and make up 50.9% of all subscribers in the dataset.
- **Gaming is flat.** It grew 40% over six years, the least of the four sectors, and slipped 0.2% in 2026.
- **The market is maturing.** Six of the 20 providers lost subscribers in 2026.

## Recommendations

- **Put retention spend into streaming first.** It combines the highest churn with the weakest growth, so each lost subscriber is the hardest to replace.
- **Use software as the benchmark.** A 5% churn rate alongside continued growth suggests that dependence on the product, more than price, keeps subscribers. Streaming providers could test bundling and usage-based value before discounting.
- **Plan for retention and expansion over acquisition.** With growth at 5.1% and six providers shrinking, future revenue is more likely to come from keeping and upselling existing subscribers than from new sign-ups.
- **Offer a way to stay.** Where churn is high, a cheaper tier or a pause option gives subscribers an alternative to cancelling.

## Skills demonstrated

- Tableau Public: dashboard design, interactive filters, layout
- Data analysis: growth, churn and retention by sector and provider
- SQL: structuring and validating the source data before export
- Data modelling: time-series structure and sector segmentation in Excel
- KPI tracking: growth rates, churn rates, retention rates
- Communicating findings: turning the numbers into recommendations

## Dashboard highlights

### Complete dashboard
![Dashboard Overview](Subscription%20Growth%20&%20Churn%20Dashboard.jpg)
All the key views on one page for the 2020 to 2026 period.

### Subscriber growth timeline
![Subscriber Growth Timeline](screenshots/Subscriber%20Growth%20Timeline.jpg)
Subscribers by provider from 2020 to 2026, showing the early surge and the slowdown after it.

### Churn rate analysis
![Churn Rate Analysis](screenshots/Churn%20Rate%20Analysis.jpg)
Churn rate by provider, sorted from highest to lowest.

### Churn and retention timeline
![Churn vs Retention Timeline](screenshots/Churn%20vs%20Retention%20Timeline.jpg)
Churn and retention rates side by side. Both are constant per provider in this dataset, so the useful comparison is between sectors.

### Retention distribution
![Retention Distribution](screenshots/Retention%20Distribution.jpg)
Retention rates across the four sectors.

### Year-on-year growth heatmap
![YoY Growth Heatmap](screenshots/YoY%20Growth%20Heatmap.jpg)
Growth by provider and year, showing where it accelerated, stalled or turned negative.

### Market share snapshot (2026)
![2026 Market Share](screenshots/2026%20Market%20Share.jpg)
Share of subscribers by sector and provider in 2026.

### Performance matrix
![Performance Matrix](screenshots/Performance%20Matrix.jpg)
Growth against churn, separating fast-growing, high-churn providers from slower, more stable ones.

### Top subscription providers
![Top 10 Providers](screenshots/Top%2010%20Providers.jpg)
The ten largest providers by subscribers.

## Files included

- `Subscription_Growth_Churn_Analysis_2020_2026.twbx`: Tableau packaged workbook with embedded data
- `Subscription_Growth_Churn_Analysis_2020_2026.xlsx`: the prepared dataset exported from SQL (subscribers, churn and retention by provider and year)
- `Subscription Growth & Churn Dashboard.jpg`: full dashboard screenshot
- `screenshots/`: individual chart screenshots

## How to view

- **Interactive dashboard:** open the `.twbx` file in Tableau Public or Tableau Desktop.
- **Quick view:** the screenshots in this README.

## Built with

**Tableau Public:** dashboard design and interactive visualisations  
**SQL:** structuring and validating the data, exported to Excel  
**Excel:** modelling and final checks
