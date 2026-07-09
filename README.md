# Customer Shopping Behavior Dashboard (Power BI)

An interactive Power BI dashboard analyzing customer shopping behavior, demographics, and purchasing patterns across product categories, seasons, and payment methods.

## 📊 Project Overview

This project explores customer-level transaction data to answer key business questions:
- Which age groups and genders spend the most, and on what categories?
- How do discounts and subscriptions affect purchase frequency?
- Which payment methods and shipping types are most popular?
- How does purchase behavior vary by season and location?
- What's the relationship between review ratings and repeat purchases?

## 🗂️ Dataset

`data/customer_shopping_behavior.csv` — ~3,900 customer transaction records with the following fields:

| Field | Description |
|---|---|
| customer_id, age, gender, age_group | Customer demographics |
| item_purchased, category, size, color | Product details |
| purchase_amount, discount_applied | Transaction value and discounting |
| location, season | Geographic and seasonal context |
| review_rating, previous_purchases, purchase_frequency_days | Customer engagement history |
| subscription_status, payment_method, shipping_type | Purchase behavior and preferences |
| frequency_of_purchases | Purchase cadence (e.g. Weekly, Fortnightly) |

## 🛠️ Tools Used

- **Power BI Desktop** — data modeling, DAX measures, interactive report pages
- **Power Query** — data cleaning and transformation
- **DAX** — calculated measures (e.g., Average Purchase Value, Repeat Purchase Rate, Discount Uptake %)

## 📈 Dashboard Highlights

- KPI cards for Total Revenue, Average Purchase Amount, and Average Review Rating
- Demographic breakdown by age group and gender
- Category and seasonal purchase trend analysis
- Payment method and shipping type preference comparison
- Subscription vs. non-subscription spending behavior
- Interactive slicers for filtering by category, season, and location

*(Screenshot of the dashboard below — see `screenshots/` folder)*

![Dashboard Overview](screenshots/dashboard_overview.png)

## 🔑 Key Insights

*(Fill in 3-5 bullet points once you've reviewed your findings, e.g.:)*
- [Age group] customers show the highest average purchase amount
- Subscribers make [X]% more frequent purchases than non-subscribers
- [Category] sees the strongest seasonal spike during [season]
- [Payment method] is the most commonly used, especially among [segment]

## 📂 How to View

1. Download `dashboard/customer_behavior_dashboard.pbix`
2. Open in [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)
3. Explore interactively using the slicers and filters on each report page

## 📬 Connect

[LinkedIn](https://www.linkedin.com/in/pijush-paul-4a6764197)
