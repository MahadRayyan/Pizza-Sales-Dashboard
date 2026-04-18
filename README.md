# 🍕 Pizza Sales Dashboard

An interactive Power BI dashboard analyzing pizza sales performance across time, size, category, and product. Tracks $817.9K in net sales with breakdowns by daily time slots, monthly trends, top-selling pizzas, and pizza size distribution — all in one clean, dark-themed view.

---

### ⚡ Technologies

- Power BI
- DAX
- Power Query

---

### 🚀 Features

- KPI cards showing **Rush Hour (12)**, **Net Sales ($817.9K)**, **Hot Selling Pizza (January — Pepperoni)**, **Monthly Avg Sales ($68.2K)**, and **Mean Sales Volume (4.1K)**
- **Monthly Sales Breakdown** — line chart tracking revenue from January through December (~$64K–$73K range)
- **Daily Sales Breakup** — donut chart splitting revenue across Morning ($45.32K), Afternoon ($486.43K), Evening ($72.63K), and Night ($213.48K)
- **Pizza Size Sales Breakup** — donut chart showing sales by size: L (19.0K), M (15.6K), S (14.4K), XL (0.6K)
- **Top 5 Selling Pizzas** — bar chart ranking Classic Deluxe, Barbecue Chicken, Hawaiian, Pepperoni, and Thai Chicken pizzas by volume
- **Sales by Pizza Category** — bar chart comparing revenue across Thai Chicken, Barbecue Chicken, California Chicken, Classic Deluxe, and Spicy Italian
- Bold dark red theme with high-contrast yellow and orange visuals for easy reading

---

### 🧠 The Process

I wanted to build a dashboard that answers the key questions for a pizza business — what's selling, when is it selling, and in what size? Started by cleaning and modeling the sales data in Power Query, then wrote DAX measures for net sales, monthly averages, mean sales volume, and rush hour calculations.

The daily sales donut was the most interesting part — splitting orders into morning, afternoon, evening, and night slots revealed that afternoons dominate sales by a huge margin ($486K vs $45K in the morning). The size breakdown confirmed that Large and Medium pizzas drive most volume, while XL barely registers. Putting it all together in a single-page layout with a consistent dark red theme made it feel like a proper business analytics tool rather than just a report.

---

### 🛠 Running the Project

1. Open `pizza_sales_dashboard.pbix` in Power BI Desktop
2. Update the data source path to point to your local dataset if prompted
3. Click **Refresh** to load the data
4. Explore monthly trends, size breakdowns, and top sellers using the visuals

---

### 📁 Preview
<img width="934" height="528" alt="image" src="https://github.com/user-attachments/assets/94bce6ca-9707-42e8-ab9a-8bafb62cd6b2" />


```
