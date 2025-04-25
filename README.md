# Task 4: Interactive Dashboard Design

## **Objective**
To design an interactive sales dashboard for business stakeholders using Power BI, with clear KPIs and visual storytelling that supports business decision-making.

---

## **Tool Used**
- **Power BI**

## **Dataset**
- `train.csv` (Source: Kaggle)

---

## **Steps Followed**

### **1. Data Preparation**
- Loaded the dataset into Power BI
- Cleaned data:
  - Removed null, blank, and duplicate rows
  - Corrected data types
  - Formatted dates using locale settings
- Created new calculated columns:
  - `OrderMonth`, `OrderYear`, `YearMonth` for trend analysis
  - `Delivery Days` using DATEDIFF
- Created key measures:
  - `Total Sales`, `Avg Sales per Order`, `Total Orders`, `Profit`

---

### **2. Dashboard Design**
- **KPIs Displayed**:
  - Total Sales, Avg Sales per Order, Total Orders (Card visuals)
- **Charts Used**:
  - Profit by Segment (Column Chart)
  - Top 10 States by Sales (Column Chart)
  - Orders by Ship Mode (Column Chart)
  - Average Delivery Days by Ship Mode (Bar Chart)
- **Interactive Features**:
  - Segment slicer for dynamic filtering
- **Design Elements**:
  - Curved borders for visuals
  - Custom image background
  - Consistent color theme

---

## **Key Insights**
- Consumer segment is most profitable
- California has the highest sales
- Standard Class is the most-used shipping mode with ~5-day delivery

---

## **Deliverables**
- Power BI Dashboard file (`.pbix`)
- PDF export of Dashboard
- Project Summary PPT (`.pptx`)
- README.md file

---

## **Outcome**
This project helped in learning how to design a professional and interactive dashboard that clearly presents data-driven business insights using Power BI.
