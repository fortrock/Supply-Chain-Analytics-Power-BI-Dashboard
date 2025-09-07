# Supply Chain Analytics – Power BI Dashboard

## Overview
This Power BI dashboard provides deep insights into supply chain performance, focusing on product sales, stock levels, order quantities, profit margins, and supplier performance.

---

## Key Metrics
- **Total Revenue:** $578K
- **Total Cost:** 58K
- **Products Sold:** 46,099
- **Average Profit Margin:** 86%
- **Stock Level:** 4,777 units

---

## Tabs & Visual Insights

### 1. Overview

- **Customer Demographics:** Revenue breakdown by Male, Female, Non-binary, Unknown.
- **Product Type Revenue:** Skincare, Haircare, and Cosmetics contributions.
- **Defect Rate Analysis:** Average defect rate by product type.
- **Revenue by Shipping Carrier:** Carrier B leads with ~$0.25M.
- **Top SKUs:** SKU51, SKU38, SKU31, SKU30, SKU12.
- **Supplier Profitability:** Supplier 3 has the highest margin (91%).

---

### 2. Product Insights

- **Order Quantities & Stock Levels** for all SKUs.
- **Lead Time Analysis** per SKU.
- **Profit Margin by Product Type:** Cosmetics slightly leads at 33.76%.
- **Price vs Products Sold:** Scatter plot to assess price-performance relationship.

---

### 2. Supplier Insights

- **Total Cost by Transportation Modes** like Sea,Air,Rail,Road
- **Average Defect Rate % by Transportation Modes**  like Sea,Air,Rail,Road
- **Profit Margin and Sum of Defect Rate by Supplier Name**
- **Supplier Name vs Stock Level** Supplier 1 lead with 1142
- **Supplier Analysis:** Cost,Manufacturing cost & Sum of Shipping Cost Of each Supplier

---

## Data Sources
- **Table:** `supply_chain_data`
- **Measures:** `_Measures` (DAX-based KPIs)

---

## How to Use
1. Download the `.pbix` file from this repository.
2. Open in [Power BI Desktop](https://powerbi.microsoft.com/desktop/).
3. Refresh the data if connected to live sources.
4. Use the slicers (SKU, Supplier) to filter views.

---

## Key Insights
- Skincare, Haircare, and Cosmetics have similar profit margins (~33% each).
- Carrier B is the primary revenue contributor among logistics partners.
- Supplier 3 offers the highest profitability (91%).

---

## Future Enhancements
- Add Supplier Lead Time & Cost Correlation.
- Forecast demand using predictive analytics.
- Integrate sustainability KPIs (carbon footprint by product type).
