# 🛠 Steps to Create a Mobile Sales Dashboard in Power BI
**1. Prepare the Data**
You need clean and structured sales data first.
**Typical columns:**

Order ID

Product Name

Brand (Samsung, Apple, etc.)

Category (Smartphone, Accessories, etc.)

Sales Amount

Units Sold

Order Date

Region

Customer Name

Customer Rating

# 👉 You can use Excel, SQL, or a CSV file to store this data.

** 2. Load Data into Power BI**
Open Power BI Desktop.

Click on Get Data → Choose Excel/CSV/SQL → Load your sales dataset.

**3. Create Relationships (if needed)**
If you have multiple tables (for example: Products table, Sales table), connect them properly through a Model view.

**4. Design the Desktop Layout**
Build visuals that show important insights:


Visual Type	Purpose
Card	Show Total Sales, Total Units Sold, Profit
Clustered Column Chart	Show Sales by Product Brand
Line Chart	Show Sales Trend Over Time
Pie Chart / Donut Chart	Show Sales Share by Region
Table	Show detailed Product-wise or Order-wise Sales
Bar Chart	Show Top 5 Best-Selling Mobiles
✅ Keep the layout simple and organized — few visuals at the top and some detailed tables below.

**5. Switch to Mobile Layout**
Power BI has a special Mobile View:

On the top bar → Click View → Mobile Layout.

Drag and drop visuals into a phone-sized canvas.

Rearrange cards, charts, and tables vertically (scroll-friendly layout).

Keep important KPIs (like Total Sales, Top Products) at the top.

Test the tap-friendly experience: no clutter, no small text.

**6. Publish and Share**
Publish your dashboard to Power BI Service (online).

Install the Power BI Mobile App (iOS or Android) and open the report — it fits perfectly on a mobile screen.

Share it with sales managers, team leaders, or executives!

# 🎯 Features to Make it Better:
Slicers/Filters: Allow filtering by Date Range, Brand, Region.

Tooltips: Hover popups showing extra details on charts.

Conditional Formatting: Highlight poor or top-performing products in red/green.

Dynamic Titles: Change titles based on selected filters (like "Sales Report for Apple" if Apple is selected).

# 🧩 Example Layout for Mobile
java
Copy
Edit
---------------------------------
| Total Sales (Card)            |
| Units Sold (Card)             |
| Profit Margin (Card)          |
|                               |
| Sales Trend (Line Chart)      |
| Top Products (Bar Chart)      |
| Sales by Region (Pie Chart)   |
|                               |
| Table: Product Details        |
---------------------------------
