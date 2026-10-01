# Insurance Policy Analytics Project

An analysis of 5,000 insurance policies, with the same dataset visualized as a dashboard in three tools: **Excel, Tableau, and Power BI**.

## Project Structure
- `excel insurance analytics`: Excel working file (raw data, pivot tables, dashboard)
- `tableau insurance analytics`: Tableau dashboard (.twbx)
- `power bi insurance analytics`: Power BI dashboard (.pbix)

## Dashboards
![Excel Dashboard](insurance%20analytics%20ss/excel-dashboard.png)
![Tableau Dashboard](insurance%20analytics%20ss/tableau-dashboard.png)
![Power BI Dashboard](insurance%20analytics%20ss/powerbi-dashboard.png)

## Dataset
The Excel file contains 5 tables, each with 5,000 records:
- Customer information (age, gender, occupation, marital status, location)
- Policy details (policy type, coverage, premium, dates, status)
- Claims (claim amount, claim status, settlement date)
- Payment history (amount, method, payment status)
- Additional fields (agent, renewal status, discount, risk score)

Note: The dataset appears to be synthetic, so category counts are close to evenly distributed.

## Tools & Techniques
- **Excel:** Pivot tables, slicers, KPI cards, interactive dashboard
- **Tableau:** Filters, calculated views, dashboard layout
- **Power BI:** Slicers, DAX measures, waterfall, treemap, donut and area charts

## Key Metrics
| Metric | Value |
|---|---
| Total policies | 5,000 |
| Total customers | 5,000 |
| Total coverage amount | 1,272,814,747 |
| Total claim amount | 251,378,846 |
| Total premium (2014-2024) | 5,261,008 |
| Claim approval ratio | 34.24% |

## Key Insights
1. **Only about a third of claims are approved.** Out of 5,000 claims, 1,712 (34.2%) are approved, 1,638 (32.8%) denied and 1,650 (33.0%) pending. The large pending share points to a claim processing backlog.
2. **Payment failures are very high.** 2,484 payments (49.7%) failed against 2,516 successful, so nearly every second payment fails.
3. **Only 33.6% of policies are active.** 1,682 are active, 1,678 terminated and 1,640 lapsed, which shows a serious customer retention issue.
4. **Health is the largest policy type** with 1,316 policies, followed by Property (1,236), Life (1,234) and Auto (1,214). The gap between types is small.
5. **Age group 26-35 has the most policies** (805) among the individual age groups. The 56 and above groups together hold 2,180 policies (43.6%).
6. **Premium grew sharply after 2014, then stayed flat, then declined.** Yearly premium stayed between about 510K and 562K from 2015 to 2022, peaked in 2022 (562,429), and fell to 475,480 in 2024, roughly 15% below the peak. The 2014 value (13,373) is only partial data.
7. **Gender split is almost equal:** Other 1,699, Male 1,677, Female 1,624.

## Recommendations
- Reduce the pending claims backlog to improve customer trust.
- Investigate the reasons for failed payments (payment method, reminders, auto-debit).
- Run retention campaigns for lapsed and terminated policies.

## How to Open the Files
- **Excel:** Open the .xlsx file in Microsoft Excel
- **Tableau:** Open the .twbx file in Tableau Desktop or Tableau Public
- **Power BI:** Open the .pbix file in Power BI Desktop

## Author
Charu Haldar
