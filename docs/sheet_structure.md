# 📘 Excel Workbook Sheet Structure

All data processing, analysis, and visualization are contained within a single Excel workbook.

---

## 📄 Sheet Breakdown

### 1️⃣ salesdata
- Original sales dataset
- No transformations applied
- Used as the source for all analysis

### 2️⃣ Cleaned_Data
- Data cleaning steps:
  - Removed null values
  - Standardized category names
  - Date formatting
- Serves as input for pivot tables

### 3️⃣ Pivot Table Sheets
Used for dashboard visuals:

- `ProfitGainedOverTime`
- `MonthlySales`
- `Top5Customers`
- `SalesByState`
- `CustomerCount`
- `SalesByCategory`


Each sheet contains:
- Pivot tables
- Pivot charts
- Supporting calculations

### 4️⃣ Dashboard
- Final interactive dashboard
- Connected to all pivot tables
- Includes slicers for:
  - Category
  - Year
