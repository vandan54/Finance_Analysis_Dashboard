# FinSight: Finance Analysis Dashboard

A professional, end-to-end Power BI business intelligence solution providing real-time insights into corporate financial transactions, customer segments, regional trends, and operational risks. 

---

## 📊 Dashboard Previews

### 1. Overview Analysis
This view tracks high-level financial metrics, monthly performance trends, and key demographic breakdowns to understand the overall health of the business.
<img width="1405" height="722" alt="Screenshot 2026-06-23 154857" src="https://github.com/user-attachments/assets/c035dcd2-c74a-457c-8619-1c517a6301f2" />


### 2. Transaction Deep-Dive
A granular tabular view allowing financial analysts to drill down into individual transaction IDs, payment types, execution status, and specific customer profiles.
<img width="1517" height="750" alt="Screenshot 2026-06-23 155759" src="https://github.com/user-attachments/assets/c76e6127-754e-4a54-9d24-d9a88f23e4f0" />


---

## 🚀 Key Business Insights & Features

*   **Executive Financial KPIs:** Instantly tracks macro-level health metrics including Total Value (₹135.62M), Total Transactions (15.029K), Average Transaction Value (₹9.02K), Fees collected (₹217.30K), and Total Tax (₹39.14K), with Year-over-Year variance benchmarks.
*   **Time-Series Trend Analysis:** Interactive line chart mapping "Total Amount by Month" to reveal seasonal surges and transaction frequency fluctuations.
*   **Risk & Operational Stability Mapping:** Ring charts visualizing transaction status (Success vs. Failed vs. Pending) alongside tabular heatmaps classifying transactional behavior (e.g., Loan EMI, Deposits, Card Payments, and Interest Credits).
*   **Demographic & Customer Segmentation:** Bar and donut chart matrices displaying distributions across customer segments (Retail, Premium, SME, Corporate, Wealth), gender classifications, and geographic performance (e.g., Maharashtra leading regional revenue with ₹19.7M).
*   **Dynamic UI Controls:** Fully equipped with interactive left-hand sidebar slicers for filtering entire report states dynamically by **Year**, **Dynamic Metric Selection**, **Occupation**, and **Category**.

---

## 🛠️ Technical Stack & Tools Used
*   **Visualization Platform:** Power BI Desktop
*   **Data Models & File Types:** `.pbix` (Power BI Report), `.csv` (Structured flat data feeds)
*   **Data Layout Engines:** Power Query (ETL transformations), DAX (Data Analysis Expressions for custom KPI time-series metrics)

---

## 📁 Repository Structure
*   `Finance Analysis.pbix` — The main, interactive Power BI file containing the report pages and data relationships.
*   `finance_transactions.csv` — Transaction history repository feed.
*   `customers.csv` — Customer profile mapping and geographic segmentation data.
*   `Pending transaction.csv` — Unresolved entries for risk tracking.
*   `Business Requirements.docx` — Project roadmap and stakeholder alignment documentation.
*
