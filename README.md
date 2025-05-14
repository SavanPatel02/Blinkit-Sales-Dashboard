# 📊 Blinkit Sales Dashboard - Power BI Project

This repository contains an interactive **Power BI dashboard** developed to analyze and visualize sales data for **Blinkit**, a leading instant delivery platform dealing in daily essential goods. The dashboard uncovers patterns across item categories, outlet types, ratings, and sales figures — helping derive actionable insights for strategic decisions.

---

## 🧠 1. Project Objective

The main objective of this project is to design a **comprehensive and data-driven dashboard** using **Power BI** that allows:

* Monitoring and analyzing **total and average sales**
* Understanding the impact of **item categories and fat content** on sales
* Exploring the **distribution of sales by outlet size, type, and location**
* Studying **outlet establishment trends**
* Evaluating **product ratings** across different item categories

This dashboard can help operations and marketing teams at Blinkit to:

* Optimize inventory based on top-selling product types
* Prioritize outlets based on location performance
* Improve customer satisfaction by tracking product ratings

---

## 🧾 2. Dataset Description

* **Total Records**: \~8,500+
* **Columns**: 25
* **Data Type**: Categorical and Numerical
* **Key Features Used**:

  * `Item Type`
  * `Item Fat Content`
  * `Item Identifier`
  * `Outlet Size`
  * `Outlet Location Type` (Tier 1, 2, 3)
  * `Outlet Establishment Year`
  * `Outlet Type` (Grocery Store, Supermarket Type 1/2/3)
  * `Item Sales` and `Item Rating`

The dataset was cleaned and loaded into Power BI using the internal data modeling and transformation features.

---

## 📈 3. Key Features and Visualizations

The dashboard is organized into **KPI cards**, **clustered bar charts**, **line graphs**, and **slicers** to give a clear understanding of business performance. Below are the major sections:

### 🔹 KPI Cards

* **Total Sales**: 1.20M
* **Average Sales**: 140.99
* **Total Number of Outlets**: 10
* **Max Individual Sales Value**: 133.10K
* **Average Product Rating**: 4

### 🔹 Visual Analytics

1. **Sales by Item Type**
   → Identifies which item categories (e.g., Fruits & Vegetables, Snack Foods, Dairy, etc.) generate the highest sales.

2. **Sales by Fat Content**
   → Compares `Low Fat`, `Regular`, `LF`, and `reg` categories based on sales volume and percentage.

3. **Sales by Outlet Type and Size**
   → Analyzes how different outlet formats (Supermarket vs Grocery Store) and sizes (Small, Medium, High) contribute to revenue.

4. **Sales by Establishment Year**
   → Shows historical performance based on the year an outlet was established (2010–2020).

5. **Outlet Identifier Analysis**
   → Bar chart showing the count of sales transactions by outlet IDs.

6. **Outlet Location Type Performance**
   → Uses `Tier 1`, `Tier 2`, and `Tier 3` to measure count of sales and average sales.

7. **Ratings by Fat Content**
   → Analyzes how item fat types impact user ratings.

### 🔘 Slicers and Filters

* `Item Type`
* `Item Fat Content`
* `Outlet Type`
* `Outlet Location Type`

These filters allow users to **interact dynamically** with the dashboard and customize views.

---

## 🛠️ 4. Tools and Technologies Used

| Tool                   | Purpose                                       |
| ---------------------- | --------------------------------------------- |
| **Power BI**           | Data modeling, transformation & visualization |
| **DAX**                | Custom calculated columns, measures, KPIs     |
| **Power Query**        | Data shaping, type conversion, filtering      |
| **Excel** *(optional)* | Data preparation (if used)                    |

---

## 📂 5. Project Structure

```
📁 Blinkit-Sales-Dashboard
│
📄 blink.pbix                 # Power BI report file
📄 Blinkit Dashboaed.pdf     # PDF snapshot of the dashboard
📄 README.md                 # This documentation file
📁 assets/                   # (Optional) Add screenshots or sample data here
```

---

## 🧹 6. Insights Delivered

* **Top-performing items** can be quickly identified for demand planning.
* Outlets in **Tier 3 locations** showed higher sales frequency, indicating potential growth markets.
* **Sales distribution** is higher among `Low Fat` items compared to `Regular`, indicating health-conscious consumer trends.
* Ratings are relatively **uniform across fat types**, but this can inform product reformulations.
* Sales trends by **establishment year** help evaluate the longevity and profitability of older outlets.

---

## 🚀 7. How to Run the Dashboard

To use this dashboard:

1. Clone this repository or download the `.pbix` file.
2. Open the file using **Power BI Desktop**.
3. Explore different views by using **filters/slicers**.
4. Hover on visuals for detailed tooltips and breakdowns.
5. Modify or extend the dashboard using Power BI’s features if needed.

---

## 🧑‍💻 8. Author

**👤 Name:** Savan Patel
**📧 Email:** *[savanpatel0208@gmail.com](mailto:your.email@example.com)*

---

## 📸 9. Dashboard Screenshots 

> 
![Screenshot 2025-05-14 103426](https://github.com/user-attachments/assets/3112bc06-f0a8-4b0f-ba8e-4d99cb54a0c0)
![Screenshot 2025-05-14 103507](https://github.com/user-attachments/assets/af08e2dc-a447-4706-b7b6-62823b4a4fc0)


---

## ⭐ 10. Feedback

If you find this project useful, consider giving it a ⭐ on GitHub and sharing it with others!
