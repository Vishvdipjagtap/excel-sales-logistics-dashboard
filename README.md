# Interactive Sales & Logistics Performance Dashboard
<img src="Screenshot.png" width="100%" alt="Dashboard Preview">

## 📊 Project Overview
This project features a fully dynamic, end-to-end Business Intelligence (BI) dashboard built entirely within Microsoft Excel. Utilizing a dataset containing nearly 10,000 retail transactions, this tool tracks key commercial health metrics, streamlines logistics analysis, and provides stakeholders with actionable insights into corporate profitability and shipping performance.

---

## 🛠️ Key Features
*   **Dynamic Visualizations:** Leverages advanced Excel charts, KPI cards, and custom formatting for rapid decision-making.
*   **Interactive Slicers:** Allows users to filter high-level numbers by time periods, geographic regions, shipment types, and product segments seamlessly.
*   **Granular Profitability Tracking:** Highlights hidden cost drivers across product categories and sub-categories.
*   **Operational Architecture:** Modeled using structured best practices, separating the analytical raw data from the logic layers and the presentation UI.

---

## 📂 Repository Structure & Workflow
The workbook is architected into four distinct modules to simulate an enterprise-level data pipeline:

| Sheet Name | Layer Type | Purpose |
| :--- | :--- | :--- |
| `dataset` | **Data Layer** | The core database containing 9,994 transactional rows covering Order Dates, Customer Segments, Regions, Shipping Modes, Sales, and Profit margins. |
| `Planning sheet` | **Design Layer** | Wireframes, color palettes, and UI/UX structural layout blueprints. |
| `Working sheet` | **Logic Layer** | Houses the Pivot Tables, lookups, and aggregate metrics feeding the front-end dashboard. |
| `Dashboard` | **Presentation Layer** | The final interactive workspace built for executives, featuring slicers, trend lines, and KPI cards. |

---

## 📈 Core Analytics Covered
1.  **Sales & Profit Performance:** Identification of high-performing vs. low-margin product lines.
2.  **Geographic Demographics:** Deep dive into high-revenue regional territories (States and Cities).
3.  **Logistics & Supply Chain:** Assessment of delivery efficiency grouped by `Ship Mode` (First Class, Second Class, Same Day, Standard Class).
4.  **Customer Segmentation:** Comparative insights between Consumer, Corporate, and Home Office revenue splits.

---

## 🚀 How to Explore the Dashboard
1. Download the `Dashboard.xlsx` file from this repository.
2. Open the file in **Microsoft Excel** (Excel 2016 or newer recommended for optimal slicer compatibility).
3. Enable Macros / Data Connections if prompted.
4. Use the floating **Slicers** on the `Dashboard` sheet to dynamically filter the visual charts.
