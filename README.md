# powerbi-airline-ops-revenue-dashboard

![Cover image showing the multi-page structure of the Power BI report.](https://github.com/BlessingUchenna891/powerbi-airline-ops-revenue-dashboard/commit/7274f77800b59e7af6d9a43c8e42e72849914878)

***

**PROJECT OVERVIEW**

This Power BI solution was developed as a comprehensive case study to address the challenge of quantifying the operational and financial impact of flight delays within the airline industry. The project links key performance indicators (KPIs) like promptness and resource consumption directly to revenue performance.

**KEY OBJECTIVES**

Diagnosis: Accurately identify the specific root causes of flight delays (e.g., Operational, Technical, Weather).

Tracking: Monitor the critical trend of On-Time Rate over time to assess management intervention effectiveness.

Impact Analysis: Determine which high-revenue flight routes are most severely impacted by delays, enabling data-driven risk management.

**TECHNICAL SOLUTIONS AND DASHBOARD PAGES**
The solution is structured across multiple linked pages to provide a seamless analytical workflow:

**Executive Overview dashboards (2 pages)** designed to work together, presenting a logical flow of information for a senior leader. They effectively separate the Performance Status (Page 1) from the Revenue and Failure Breakdown (Page 2).
![Screenshot of Executive Overview (page 1) showing the trend line and column chart for performance status](https://github.com/BlessingUchenna891/powerbi-airline-ops-revenue-dashboard/blob/main/Executive-Overview-page1.png)
![Screenshot of Executive Overview (page 2) showing 2 stacked bar charts presenting Revenue distribution by route and categories of delay in the airline.](https://github.com/BlessingUchenna891/powerbi-airline-ops-revenue-dashboard/blob/main/Executive-Overview-Page2.png)

**Operations Performance:** Focuses on high-impact KPIs (e.g., 15% On-Time Rate, 25.38 AVG Delay mins) and uses a stacked bar chart to instantly diagnose Operational issues as the dominant cause of delays.

**Detailed Analysis (Operations Performance 3 (Page 5)):** Provides transactional tables with conditional formatting to allow users to drill down to individual flight performance, revenue groups, and delay severity levels.

**Revenue Performance (Page 6):** Links operational metrics to financial results. Key features include tracking Total Revenue, AVG Revenue, and Fuel Used. The page features a critical visual showing AVG Delay (mins) by Route, highlighting high-delay routes that threaten revenue streams (e.g., Abuja-Lagos).

**Data Modeling & UX:** Ensured data integrity by creating necessary time intelligence columns (Month Num) to correctly sort time-series visuals chronologically.

**RESULTS & DEMONSTRATED IMPACTS**

**1. Actionable Intelligence:** Provided clear data that allows management to shift focus from merely observing delays to prioritizing procedure review specifically in the Operational and Technical departments.

**2. Risk Management:** Enabled the business to quantify the risk of operational failure on a route-by-route basis, informing resource allocation and scheduling decisions.

**3.Technical Proficiency:** Showcases advanced skills in DAX, Data Modeling, Waterfall charts, and Dual-Axis visualization for effective business storytelling.

**SKILLS & TECHNIUES DEMONSTRATED**

**Power BI Desktop:** End-to-end report design and development.

**Data Modeling & DAX:** Creation of a robust model, including necessary time intelligence columns and calculated measures (e.g., On-Time Rate, Delay Status, Delay Category, Revenue Group etc.).

**Visualization:** Advanced use of Dual-Axis Charts (Line/Column), Waterfall Charts, and effective use of color and conditional formatting for business impact.

**Data Storytelling:** Designing a logical report flow from high-level summary $\rightarrow$ root cause analysis $\rightarrow$ financial consequence.

📥 **TO VIEW THE REPORT**

The fully interactive Power BI Desktop file is available for download in this repository:
[Download the Interactive Power BI Dashboard (.pbix)](https://github.com/BlessingUchenna891/powerbi-airline-ops-revenue-dashboard/blob/main/Airline-Operations-Performance-Analysis-for%20ValueJet-(Jan%20to%20Mar)-Mock%20Project.pbix)

**ANALYTICAL WORKFLOW (The Walkthrough Images)
**

**1. Executive Status and Trend Analysis (Image A)**
This page immediately assesses the health of the operation, establishing the critical decline in On-Time Rate and diagnosing the dominant root cause.
![Screenshot of Operations Performance 2 showing the trend line and stacked bar chart for delay reasons.](https://github.com/BlessingUchenna891/powerbi-airline-ops-revenue-dashboard/blob/main/Operations-Performance-2.png)
