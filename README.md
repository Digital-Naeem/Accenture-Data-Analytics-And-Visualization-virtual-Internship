# Accenture-Data-Analytics-And-Visualization-virtual-Internship
This repository showcases my work on Accenture's Data Analytics virtual experience with Forage, aiding "Social Buzz," a global unicorn company, in harnessing vast data through dashboards and presentations.
## Task 1 -
### Understanding the Project: 
**A data analyst bridges the gap between business insights and raw data.**
- Mae Mulligan, Managing Director at Accenture, is leading the collaboration with Social Buzz and has analyzed the project brief to align team efforts.
- A project kick-off meeting with Accenture's internal team is scheduled for tomorrow morning to initiate the work efficiently.

### About Social Buzz: 
Social Buzz is a rapidly growing enterprise facing challenges due to their scaled operations. They currently lack sufficient internal resources to manage their growth effectively. *About Client* : [Social Buzz](https://github.com/Digital-Naeem/Accenture-Data-Analytics-And-Visualization-virtual-Internship/blob/main/Data_Analytics%20Brief.pdf)

### Tasks Assigned to Accenture:
>- Perform an in-depth audit of big data practices.
>- Offer strategic advice for an IPO (Initial Public Offering).
>- Analyze trends in their most popular content.

### Accenture Project Team :
<img src = "Project Team.png">

### Task for Data Analyst: 
Analyze sample data sets with visualizations to identify the popularity of different content categories. 
>- **Specifically, the client seeks an analysis highlighting their top 5 most popular content categories.**
## Task 2 -
### Simplified Approach to Data Analysis: 
Not all datasets may be necessary to address specific business questions. The initial step is to use a [data model](https://github.com/Digital-Naeem/Accenture-Data-Analytics-And-Visualization-virtual-Internship/blob/main/Data%20model.pdf) to identify only the relevant datasets needed to determine the top 5 most popular content categories, thereby avoiding unnecessary complexity.

### Datasets Identified for Analysis:
>- Reaction Score: Quantifies the popularity of content.
>- Content ID
>- Reaction Types
>- Content Type
>- Category

### Data Cleaning Steps Explained: 
**To ensure accuracy and relevance in the analysis, the following steps were taken:**
- Eliminating rows with missing values to maintain data integrity.
- Modifying column data types for consistency.
- Removing irrelevant columns that do not contribute to answering the business question.
- Each column was critically evaluated for its relevance, and those with no clear purpose were excluded.
- **Effective Merging:** The cleaned datasets were combined into one final spreadsheet using formulas such as VLOOKUP and SUMIF, ensuring streamlined analysis and precision.

**Result of Data Cleaning: Three refined datasets were created:**
- [Reaction Types](https://github.com/Digital-Naeem/Accenture-Data-Analytics-And-Visualization-virtual-Internship/blob/main/ReactionTypes.csv)
- [Reactions](https://github.com/Digital-Naeem/Accenture-Data-Analytics-And-Visualization-virtual-Internship/blob/main/Reactions.csv)
- [Content](https://github.com/Digital-Naeem/Accenture-Data-Analytics-And-Visualization-virtual-Internship/blob/main/Content.csv)

### Data Modeling Process: 
1. Merging Data:
Combined three cleaned datasets into a single, unified dataset.
Base Table: Used the Reaction Table as the foundation.
- **Merged relevant columns from:**
>- The Content dataset.
>- The Reaction Types dataset.
**Hint:** Utilized the VLOOKUP formula for effective and accurate merging.
2. Score Calculation:
Added up the total scores for each category using the SUMIF formula.
This helped in determining the most popular content categories.

### Result of Data Modeling:
End Product: A consolidated spreadsheet that includes:
>- A cleaned and unified dataset prepared for analysis.
>- Top 5 most popular content categories, identified based on their cumulative scores.

### Final Deliverables:
- **A refined, [cleaned dataset](https://github.com/Digital-Naeem/Accenture-Data-Analytics-And-Visualization-virtual-Internship/blob/main/Cleaned%20Dataset.xlsx), ready** for further analysis.
- Identification of the **top 5 content categories with the largest popularity**, providing actionable insights.
