# Interactive Sales Dashboard – Power BI

## **Objective**
Design an interactive Power BI dashboard for business stakeholders that provides key insights into sales performance.

---

## **Tool Used**
- Power BI

## **Dataset**
- `train.csv` (Source: Kaggle)

---

## **Data Preparation**
- Loaded the dataset into Power BI.
- Cleaned the data by:
  - Removing null values, blank rows, and duplicate records.
  - Correcting data types for accurate analysis.
  - Applied locale settings for proper date formatting.
- Created new calculated columns and measures:
  - `OrderMonth`, `OrderYear`, `YearMonth` (for trend analysis)
  - `Avg Sales per Order`, `Total Orders`, `Total Sales`, `Profit`
  - `Delivery Days` (calculated using DATEDIFF between `Ship Date` and `Order Date`)

---

## **Dashboard Design**

### **KPIs Displayed**
- **Total Sales**
- **Average Sales per Order**
- **Total Orders**

### **Charts Used**
- **Sales by Region** (Column Chart)
- **Sales by Category** (Bar Chart)
- **Profit by Segment** (Column Chart)
- **Top 10 States by Sales** (Column Chart)
- **Orders by Ship Mode** (Column Chart)
- **Average Delivery Days by Ship Mode** (Bar Chart)

### **Interactive Elements**
- **Segment Slicer** for dynamic filtering

### **Design Features**
- Curved borders on visuals
- Visual backgrounds removed
- Custom image used as page background

---

## **Deliverables**
- Power BI Dashboard file (`.pbix`)
- PDF export of Dashboard
- Project Summary PPT (`.pptx`)
- README.md file

---

## **Outcome**
This dashboard helps business stakeholders monitor and evaluate key sales metrics and performance indicators in a visually appealing and interactive manner.