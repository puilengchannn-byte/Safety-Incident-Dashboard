## Safety Incident Dashboard (Portfolio Project) 

**Note:** This is a case study exercise. The dataset is completely synthetic/dummy data created to match the structure of the original assessment. The technical approach, data model design, and DAX logic are authentic.

**What I did:**
- Imported incident data into Power BI
- Created KPI cards tracking incident rates by severity and region
- Built time-series chart to show incident trends
- Added bar chart breaking down incidents by root cause
- Implemented filters/slicers for interactive exploration
- Designed multi-page layout for different audiences
- 
**Dashboard Structure:**
- Multi-page layout (Safety Overview + Primary Safety Risks)
- Cross-page filtering using slicers (Year, Country, Root Cause)
- Consistent color scheme and visual hierarchy

**Visualizations:**
- KPI cards with dual metrics (counts + percentages)
- Time-series line chart tracking incidents across 2018-2020
- Categorical bar charts (root cause, country comparison)
- Stacked/grouped bar charts for incident category analysis
- Conditional formatting on cards for visual emphasis

**Data Handling:**
- Imported Excel data with incident-level granularity
- Created calculated columns or measures for percentage rates
  (e.g., `Incident Rate = Incidents / Total Incidents`)
- Structured data to enable filtering by Year, Country, Root Cause
- Used aggregations to roll up counts by category

**Interactivity:**
- Implemented slicer-based filtering across both pages
- Set up visual-to-visual interactions (filtering updates all related charts)
- Drill-down capability through categorical hierarchies (Month, Year)

**Design Decisions:**
- Chose line chart for trend analysis (shows momentum over time)
- Used bar charts for categorical comparison (easier to rank root causes)
- Placed KPIs at top for executive-level quick scan
