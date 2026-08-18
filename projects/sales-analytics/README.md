# 📊 Sales Analytics & CRM Pipeline Performance Dashboard

**Focus Area:** B2B Sales Operations, Pipeline Velocity & Conversion Optimization  
**Tools Demonstrated:** Power BI, Advanced Excel (Pivot Tables, VLOOKUP), Salesforce / HubSpot Data Analytics  
**Objective:** Provide executive revenue leaders with real-time visibility into lead progression, conversion bottlenecks, and pipeline revenue velocity.

---

## 🎯 Business Problem & Context

When managing a high-volume pipeline of **500+ prospective monthly leads**, sales leaders often struggle with:
* **Pipeline Stagnation:** Inability to identify where deals stall in the sales funnel.
* **Inconsistent Lead Quality:** Difficulty isolating which lead sources yield the highest conversion velocity.
* **Inaccurate Revenue Forecasting:** Relying on subjective rep estimates rather than data-driven conversion rates.

---

## 🛠️ Data Model & Metrics Framework

To solve this, I designed a pipeline tracking framework analyzing **four key performance metrics**:

| Metric | Calculation / Definition | Business Impact |
| :--- | :--- | :--- |
| **Pipeline Velocity** | $( \text{Qualified Leads} \times \text{Win Rate \%} \times \text{Avg Deal Value} ) \div \text{Sales Cycle Length (Days)}$ | Measures the dollar amount of revenue moving through the pipeline daily. |
| **Stage Conversion Rate** | $(\text{Deals Advanced to Next Stage} \div \text{Total Deals in Stage}) \times 100$ | Pinpoints specific drop-off points in discovery and demo stages. |
| **Lead Source ROI** | $\text{Closed-Won Revenue Generated} \div \text{Total Source Outreach Effort}$ | Identifies high-performing outbound channels (e.g., Cold Calling vs. LinkedIn). |
| **Data Hygiene Score** | Percentage of CRM fields populated without duplicates or missing values | Ensures forecast reliability and reporting accuracy. |

---

## 📈 Sample Dashboard Insights & Actionable Outcomes

Using simulated CRM data modeling 500+ monthly outbound opportunities, the dashboard reveals key strategic insights:

```text
+-----------------------------------------------------------------------------------+
|                            B2B PIPELINE PERFORMANCE OVERVIEW                       |
+-----------------------------------------------------------------------------------+
| Total Leads Processed: 520   | Avg Conversion Velocity: 18 Days                   |
| Monthly Recurring Revenue (MRR): $12,000+ USD | Overall Win Rate: 60%            |
+-----------------------------------------------------------------------------------+
| STAGE BREAKDOWN:                                                                  |
|  [Cold Prospecting] ──► 520 Leads (100%)                                         |
|  [Qualified Discovery] ──► 208 Leads (40% Conversion)                             |
|  [Demo / Pitch] ──► 125 Deals (60% Conversion)                                    |
|  [Closed-Won] ──► 75 Deals (60% Win Rate)                                         |
+-----------------------------------------------------------------------------------+
