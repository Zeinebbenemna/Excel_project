# Excel_project
# Access to Drinking Water — Integrated Data Project

## Overview
This project analyzes global access to safe and affordable drinking water using datasets from the WHO/UNICEF Joint Monitoring Programme (JMP). It is divided into two major phases:
**Understanding the Data** and **Transforming the Data**. Together, these phases provide a complete picture of water accessibility across countries, population groups, and regions, as well as how access has evolved over the 2000–2020 period.

---

## 1. Understanding the Data (2020 Snapshot)

This first phase focuses on exploring a single-year dataset to gain familiarity with the structure of the data and the differences in water access across population types.

### Key Steps
- Imported and cleaned the dataset to correct formatting issues.
- Examined all baseline features, including national, urban, and rural population values and their corresponding water service levels.
- Created additional helper features to support deeper analysis (e.g., rounded populations, computed shares, and adjusted access metrics).
- Compared dataset population figures with global 2020 estimates.
- Analyzed variations in water access between national, urban, and rural areas.
- Built visualizations such as line charts, box plots, and stacked bar charts to explore how population size and area type influence access.
- Performed income-group analysis using pivot tables to investigate how water access correlates with national income categories.

This section establishes a clear understanding of the dataset's structure and key patterns in water service accessibility.

---

## 2. Transforming the Data (2000–2020 Time Series)

The second phase extends the analysis to a longitudinal dataset covering 20 years. This enables trend analysis and measurement of progress toward Sustainable Development Goal 6.

### a. Year Representation
- Imported the 2000–2020 dataset and checked how many years were recorded for each country.
- Calculated the time gaps between recorded observations.
- Summarized these findings in a summary sheet and visualized the year distribution.

### b. Annual Rates of Change (ARC)
- Added new features (ARC_n, ARC_r, ARC_u) to measure yearly changes in water access for national, rural, and urban populations.
- Ensured ARC calculations only occurred between entries belonging to the same country and handled missing or invalid values.
- Summarized ARC averages, minimums, and maximums to identify general trends in improvement or decline.

### c. Access by Area Over Time
- Rounded access values to identify where full access (100%) had been reached.
- Created indicators marking countries with full access for national, rural, and urban populations.
- Counted countries with zero change, positive change, and negative change in access.
- Calculated differences between rural and urban ARC values and visualized the distribution.

### d. Access by Region
- Imported an external region classification and merged region information into the dataset using lookup functions.
- Summarized, for each region:
  - number of countries,
  - average national ARC,
  - average rural ARC,
  - average urban ARC.
- Built a visualization comparing national ARC, rural ARC, population size, and region to uncover regional patterns.

---

## Purpose of the Project
This integrated project transforms raw water access data into meaningful, actionable insights. By combining snapshot and historical analysis, it provides a comprehensive understanding of where progress is occurring, where it is stalled, and which populations are being left behind. The findings contribute directly to discussions around global development and Sustainable Development Goal 6: Clean Water and Sanitation.

