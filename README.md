# PowerBi_Shopnest-
Interactive Power BI dashboard analyzing ShopNest e-commerce sales, delivery performance, product ratings &amp; regional trends | Skillovilla Data Analytics Capstone | Score: 100/100

# 🛍️ ShopNest Store Analytics Dashboard — Power BI Capstone

> **Course:** Skillovilla Data Analytics Program  
> **Score Achieved:** 100 / 100 🏆  
> **Tools Used:** Microsoft Power BI, DAX, Power Query  

---

## 📌 Project Overview

This project presents a comprehensive, interactive **Power BI dashboard** built on the **ShopNest Store dataset** — an e-commerce platform based in Portugal. The dashboard addresses 8 core business analytics tasks covering sales performance, delivery efficiency, customer behavior, product quality, and regional trends.

The goal was to transform raw relational data across 9 interconnected datasets into actionable business insights through well-designed, navigable visuals — complete with drill-through cross-report functionality and dynamic slicers.

---

## 📂 Files in This Repository

| File | Description |
|---|---|
| `ShopNest_Sales_Dashboard.pbix` | Interactive Power BI Dashboard file |
| `ShopNest_Store_Sales_Dashboard_Report.docx` | Detailed analytical report covering all 8 tasks |

---

## 🗂️ Dataset Description

The dashboard is built on **9 relational datasets** integrated using a **star-schema-like data model**, with the Orders table as the central fact table:

| Dataset | Description |
|---|---|
| Customers | Customer location information |
| Geolocation | Geographic coordinates of zip codes |
| Orders | Order details and timestamps |
| Order Items | Products included in each order |
| Order Payments | Payment methods and values |
| Order Reviews | Customer review scores |
| Products | Product details and categories |
| Sellers | Seller information |
| Product Category Translation | Portuguese → English category names |

---

## 📊 Dashboard Structure

The dashboard is organized into **3 main pages** + **1 drill-through page**:

### 1. 🏠 Executive Overview
High-level KPIs: **Total Sales, Average Rating, Total Orders, Net Revenue**
- Top 10 Product Categories by Sales
- State-Wise Sales Map
- Seasonal Sales Patterns (Quarterly)
- Yearly Revenue Trend
- Payment Method Distribution

### 2. ⚙️ Operational Analysis
Delivery efficiency and order volume trends:
- Monthly Comparison of Delayed vs On-Time Orders *(with Drill-through)*
- Category-Wise Delayed Orders Count
- Monthly Orders Trend
- Customer State-Wise Order Volume

### 3. 📦 Product Insights
Product performance and customer feedback:
- Top 10 Highest-Rated & Bottom 10 Lowest-Rated Products
- State-Wise Most Popular Product Categories (Map)

### 🔍 Delivery Details *(Drill-through Page)*
Accessible from the Monthly Comparison chart:
- State-Wise Delivery Delays in Portugal
- Rating Impact with respect to Delays
- Month-wise Slicer for granular analysis

> **Navigation Note:** Pages are switched using the purple rectangle buttons under each page title. Active page titles highlight in white. Slicers on the side panel filter by **Year, Product Category, Payment Method, and Customer State.**

---

## ✅ Analytical Tasks & Key Insights

### Task 1 — Top Categories by Total Price
- **Health & Beauty** is the highest revenue-generating category.
- **Watches & Gifts** and **Bed, Bath & Table** are strong runners-up.
- The top 10 categories together represent the majority of total store sales.

### Task 2 — Delayed Orders Analysis
- **Bed, Bath & Table** and **Health & Beauty** have the highest delayed order counts.
- Furniture categories show notable delays due to size and shipping complexity.
- Delays are concentrated in a few high-demand categories rather than spread evenly.

### Task 3 — Monthly Comparison of Delayed vs On-Time Orders
- Delays were highest in **February, March, and November**.
- **August** recorded the highest on-time delivery rate.
- Order volume alone doesn't directly predict delays — logistics efficiency plays a bigger role.

### Task 4 — Payment Method Analysis
- **Credit Card** is the most commonly used payment method by far.
- **Boleto** ranks second, showing reliance on bank-based payments.
- **Debit Card** has the lowest usage among all methods.

### Task 5 — Product Rating Analysis
- Entertainment, children's clothing, and books categories receive the **highest ratings**.
- Security equipment, office furniture, and clothing categories receive comparatively **lower ratings**.

### Task 6 — State-Wise Sales Analysis
- **São Paulo, Rio de Janeiro, and Minas Gerais** are the highest-selling states.
- **Roraima, Amapá, and Acre** show the lowest sales — consistent with lower population and e-commerce penetration.

### Task 7 — Seasonal Sales Patterns (Quarterly)
| Quarter | Sales |
|---|---|
| Q1 (Jan–Mar) | R$ 3.5M |
| Q2 (Apr–Jun) ⬆️ Peak | R$ 4.2M |
| Q3 (Jul–Sep) | R$ 3.4M |
| Q4 (Oct–Dec) ⬇️ Lowest | R$ 2.5M |

### Task 8 — Revenue Analysis (Yearly)
| Year | Revenue |
|---|---|
| 2016 | R$ 49,785.92 |
| 2017 | R$ 6,155,806.98 |
| 2018 | R$ 7,386,050.80 |
| **Total Net Revenue** | **R$ 16.01 Million** |

Revenue grew dramatically from 2016 to 2018, indicating rapid platform adoption and business scaling.

---

## 💡 Conclusion

The ShopNest Dashboard provides a complete, interactive view of the store's business performance — from macro-level revenue trends down to product-level customer satisfaction. Key takeaways include:
- Sales are concentrated in major urban regions of Portugal.
- A few high-demand categories dominate both revenue and delivery delays.
- Delivery performance is driven more by operational logistics than by raw order volume.
- The platform shows strong year-over-year growth from 2016 to 2018.

---

## 🚀 How to Open

1. Download the `.pbix` file.
2. Open it in **Microsoft Power BI Desktop** (free download at [powerbi.microsoft.com](https://powerbi.microsoft.com)).
3. Use the navigation buttons and slicers to explore the dashboard interactively.

---

*Built as part of the Skillovilla Data Analytics Program Capstone Project.*
