# powerbi-airline-ops-revenue-dashboard

![Cover image showing the multi-page structure of the Power BI report.](https://github.com/BlessingUchenna891/powerbi-airline-ops-revenue-dashboard/blob/main/Cover-hero-shot.png)

***

**PROJECT OVERVIEW**

This Power BI solution is a mock project I developed as a comprehensive case study to address the challenge of quantifying the operational and financial impact of flight delays within the airline industry (Valuejet). The project links key performance indicators (KPIs) like promptness and resource consumption directly to revenue performance.

**KEY OBJECTIVES**

Diagnosis: Accurately identify the specific root causes of flight delays (e.g., Operational, Technical, Weather).

Tracking: Monitor the critical trend of On-Time Rate over time to assess management intervention effectiveness.

Impact Analysis: Determine which high-revenue flight routes are most severely impacted by delays, enabling data-driven risk management.

**SITUATION & PROBLEM**

**The Goal:** Design a comprehensive performance dashboard to help airline management monitor flight promptness, identify root causes of delays, and measure the financial impact of operational issues.

**The Challenge:** Data was siloed; there was no clear, unified view to connect the high-level 85% Delay Rate to the specific routes, causes, and revenue effects.

**TECHNICAL SOLUTIONS AND DASHBOARD PAGES**
The solution is structured across multiple linked pages to provide a seamless analytical workflow:

**Executive Overview dashboards (2 pages)** designed to work together, presenting a logical flow of information for a senior leader. They effectively separate the Performance Status (Page 1) from the Revenue and Failure Breakdown (Page 2).
![Screenshot of Executive Overview (page 1) showing the trend line and column chart for performance status](https://github.com/BlessingUchenna891/powerbi-airline-ops-revenue-dashboard/blob/main/Executive-overview-1.png)
![Screenshot of Executive Overview (page 2) showing 2 stacked bar charts presenting Revenue distribution by route and categories of delay in the airline.](
**Operations Performance:** Focuses on high-impact KPIs (e.g., 15% On-Time Rate, 25.38 AVG Delay mins) and uses a stacked bar chart to instantly diagnose Operational issues as the dominant cause of delays.

**Revenue Performance (Page 6):** Links operational metrics to financial results. Key features include tracking Total Revenue, AVG Revenue, and Fuel Used. The page features a critical visual showing AVG Delay (mins) by Route, highlighting high-delay routes that threaten revenue streams (e.g., Abuja-Lagos).

**Detailed Analysis (Operations Performance 3 (Page 5)):** Provides transactional tables with conditional formatting to allow users to drill down to individual flight performance, revenue groups, and delay severity levels.

**Data Modeling & UX:** I ensured data integrity by creating necessary time intelligence columns (Month Num) to correctly sort time-series visuals chronologically.

**RESULTS & DEMONSTRATED IMPACTS**

**1. Actionable Intelligence:** Provided clear data that reduces time spent on data collection and allows management to immediately shift focus from merely observing delays to prioritizing procedure review specifically in the Operational and Technical departments.

**2. Risk Management:** Enabled the business to quantify the risk of operational failure on a route-by-route basis, informing resource allocation and scheduling decisions.

**3.Technical Proficiency:** Showcases advanced skills in DAX, Data Modeling, Waterfall charts, and Dual-Axis visualization for effective business storytelling.

**SKILLS & TECHNIUES DEMONSTRATED**

**Power BI Desktop:** End-to-end report design and development.

**Data Modeling & DAX:** I leveraged DAX to build robust measures, including complex logic for the On-Time Rate (15%), On-Time Status, Delay Rate, Top Delayed Route, Top Revenue Route, and conditional logic for classifying delays into Severe, Moderate, and Minor categories, revenue into High, Medium and Low Revenue, derived On-Time Status (Good/Bad) etc.

**Visualization:** I utilized advanced visualization techniques, including Dual-Axis Charts (Line/Column) to compare passengers vs. revenue yield, and Waterfall Charts to clearly isolate route revenue contribution. I also applied conditional formatting to instantly highlight operational failure (Red for 85% Delay Rate)

**Data Storytelling:** I designed a logical report flow from Executive Summary $\to$ Diagnosis $\to$ Business Impact.

**ANALYTICAL WORKFLOW (The Walkthrough Images)**

**1. Executive Status and Trend Analysis (Image A)**
This page immediately assesses the health of the operation, establishing the critical decline in On-Time Rate and diagnosing the dominant root cause.
![Screenshot of Operations Performance 2 showing the trend line and stacked bar chart for delay reasons.](https://github.com/BlessingUchenna891/powerbi-airline-ops-revenue-dashboard/blob/main/Operations-Performance-2.png)

**2. Operational Detail and Failure Classification (Image B)**
The detailed table view provides analysts the ability to drill down into the transactional data, identifying specific flights, calculating delay severity, and linking delays to revenue groups.
![Screenshot of the detailed Operations Performance (page 5) table with color-coded severity.](https://github.com/BlessingUchenna891/powerbi-airline-ops-revenue-dashboard/blob/main/Detailed-Operations-Performance.png)

**3. Financial and Risk Assessment (Image C)**
This final page links operational failure directly to business cost and revenue risk, highlighting the financial metrics and identifying which high-revenue routes are suffering the highest average delays.

![Screenshot of the Revenue Performance Dashboard linking revenue and AVG delay by route.](https://github.com/BlessingUchenna891/powerbi-airline-ops-revenue-dashboard/blob/main/Revenue-Performance.png)

📥 **TO VIEW THE REPORT**

The fully interactive Power BI Desktop file is available for download in this repository:
[Download the Interactive Power BI Dashboard (.pbix)](https://github.com/BlessingUchenna891/powerbi-airline-ops-revenue-dashboard/blob/main/Airline-Operations-Performance-Analysis-for%20ValueJet-(Jan%20to%20Mar)-Mock%20Project.pbix)
