# Laboratory Work 1 - Introduction to Business Intelligence & Power BI
# BASIC SALES DATA

Step 1: Quick Visualization
1. Drag Sales into canvas
2. Power BI automatically creates a visual
   
 Question:
 
● What type of chart was created?
### Power BI shows a clustered column chart when you drag a numeric field like Sales onto the canvas.
● What does it show?
### It shows the total (Sum) of Sales for the entire dataset.

----
Step 2: Create a Sales by Region Chart
1. Click blank canvas
2. Select Clustered Column Chart

3. Drag:
   
○ Region → X-axis

○ Sales → Values

Question:

● Which region has highest sales?
### _WEST_ Region has the highest sales

----

Step 3: Sales by Category
1. Insert a Pie Chart
2. Drag:
   
○ Category → Legend

○ Sales → Values

Question:

● Which category dominates?
### _Electronics_ dominate the sales with over 90K or 40.82% of the overall sales.
● Is the distribution balanced?
### _Mostly Balance_ but not perfectly as two categories (Electronics and Furniture) are fairly balanced with each other, but Office Supplies lags behind, so overall the distribution is slightly skewed, _not fully balanced_.

----

Step 4: Sales Over Time
1. Insert Line Chart
2. Drag:
   
○ Date → X-axis

○ Sales → Values

Question:
- Is there growth?
### No. There is no growth shown in the chart.
- Any noticeable trend?
### Yes — a downward (declining) trend.

Sales are high in 2024 (around 0.2M) and then Sales drop significantly in 2025 (close to 0.02–0.03M). The line slopes sharply downward, indicating a strong decrease year over year

📌 Interpretation:

_Sales declined from 2024 to 2025_

----

## PART 4: Basic Data Insight Interpretation
Students must now interpret visuals.

Question:
- Which region contributes most revenue?
  ### The _West region_ is the top revenue contributor, though the differences between regions are not very large.
- Which product category performs best?
  ### _Electronics_ is the best performing category
- Are sales consistent across dates?
  ### _No_ , sales are not consistent.
- What business recommendation can you suggest?
  ### Maintain strong marketing and customer retention strategies in West Region and focus more in Electronics. Investigate also the sales drop in 2025 for future improvement. Boost weaker regions by regional promotions or localized strategies.
----
## LABORATORY QUESTIONS
### Part A – Technical Questions
1. What are the five columns in the dataset?
- ### DATE, PRODUCT, CATEGORY, REGION and SALES.
3. What data type is assigned to the “Sales” column?
- ### DECIMAL NUMBER
5. Which Power BI view allows you to see raw data?
- ### DATA VIEW
7. What chart type is best for showing trends over time?
- ### LINE CHART
9. What aggregation is automatically applied to Sales?
- ### SUM OF SALES

### Part B – Analytical Questions
6. Which region has the highest total sales?
- ### WEST REGION has the highest total sales.
7. Which category has the lowest performance?
- ### OFFICE SUPPLY has the lowest performance. 
9. Are sales increasing, decreasing, or stable?
- ### DECREASING
11. If you were a manager, which region would you prioritize?
- ### WEST REGION, as it has the highest revenue contributor and has strong marketing performance.
13. Provide one actionable recommendation based on the data.
- ### Focus marketing and inventory investment on Electronics in the West region.

----
# ENHANCEMENT SECTION
----
**Task 1: Add a Card Visualization**
1. Insert Card
2. Drag Sales
3. Format:
- Increase font size
- Change title to “Total Sales”

**Question:**
- What is the total sales amount?
  ### Total Sales is _220K_
---
**Task 2: Add Slicer**
1. Insert Slicer
2. Drag Region
3. Test filtering
**Question:**
- What happens to other visuals when you click a region?
 ### All other visuals update automatically to show data only for the selected region.
- Why is filtering important in BI?
  ### It is important in enable to focus analysis and helps identify regional, product or time-based paterns for users to compare segments easily.
---
**Task 3: Sort Sales**
1. Click Region Chart
2. Click three dots (...)
3. Sort by Sales Descending
   
**Question:**
- Does sorting improve readability?
  ### _YES_. It improves sorting readability.
- Why?
  ### For better and easier comparison and reduces time in interpreting performances.
