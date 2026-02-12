# Laboratory Work 1 - Introduction to Business Intelligence & Power BI

**Student Name:** [Your Name Here]
**Student ID:** [Your ID Here]
**Date:** [Date of Submission]

---

## Activity Overview
**Objective:** To import CSV data into Power BI, identify dataset structures, create basic visualizations, and generate simple insights to understand how BI transforms raw data into meaningful information.

**File Used:** `LW1_Basic_Sales_Data.csv`

---

## Part 1 & 2: Loading Data and Interface

### Data View Verification
*Screenshot of the Data View showing all columns correctly formatted.*

![Data View and Column Validation](screenshots/part1_dataview.png)

**Data Type Checks:**
* **Date:** Formatted as Date.
* **Sales:** Formatted as Decimal Number.
* **Product/Category/Region:** Formatted as Text.

---

## Part 3: Creating Auto-Generated Visuals

### Step 1: Quick Visualization
*Screenshot of the first visual created by dragging "Sales" to the canvas.*

![Quick Visualization](screenshots/part3_step1_quickvis.png)

**Questions:**
* **What type of chart was created?**
    * *Dummy Answer: Power BI automatically created a Clustered Column Chart (or Bar Chart).*
* **What does it show?**
    * *Dummy Answer: It shows the total sum of sales across the entire dataset represented as a single bar.*

### Step 2: Sales by Region Chart
*Screenshot of the Clustered Column Chart showing Sales by Region.*

![Sales by Region Chart](screenshots/part3_step2_region.png)

**Questions:**
* **Which region has highest sales?**
    * *Dummy Answer: The "North" region has the highest sales bar compared to the others.*

### Step 3: Sales by Category
*Screenshot of the Pie Chart showing Sales by Category.*

![Sales by Category Pie Chart](screenshots/part3_step3_category.png)

**Questions:**
* **Which category dominates?**
    * *Dummy Answer: The "Electronics" category dominates the chart with the largest slice.*
* **Is the distribution balanced?**
    * *Dummy Answer: No, the distribution is not balanced; "Electronics" takes up 60% of the chart while "Clothing" only takes up 10%.*

### Step 4: Sales Over Time
*Screenshot of the Line Chart showing Sales over Date.*

![Sales Over Time Line Chart](screenshots/part3_step4_line.png)

**Questions:**
* **Is there growth?**
    * *Dummy Answer: Yes, there is a visible upward trend from January to December.*
* **Any noticeable trend?**
    * *Dummy Answer: Sales seem to spike significantly at the end of every quarter.*

---

## Part 4: Basic Data Insight Interpretation

* **Which region contributes most revenue?**
    * *Dummy Answer: Based on the column chart, the North Region contributes the most revenue.*
* **Which product category performs best?**
    * *Dummy Answer: Electronics is the best performing category.*
* **Are sales consistent across dates?**
    * *Dummy Answer: No, sales fluctuate. There are peaks in the middle of the month and dips at the start.*
* **What business recommendation can you suggest?**
    * *Dummy Answer: Since the North Region is performing well, we should investigate their marketing strategy and apply it to the lower-performing South Region.*

---

## Laboratory Questions

### Part A - Technical Questions

**1. What are the five columns in the dataset?**
* *Answer: Date, Product, Category, Region, Sales.*

**2. What data type is assigned to the "Sales" column?**
* *Answer: Decimal Number.*

**3. Which Power BI view allows you to see raw data?**
* *Answer: Data View.*

**4. What chart type is best for showing trends over time?**
* *Answer: Line Chart.*

**5. What aggregation is automatically applied to Sales?**
* *Answer: Sum (Summation).*

### Part B - Analytical Questions

**6. Which region has the highest total sales?**
* *Dummy Answer: The West Region.*

**7. Which category has the lowest performance?**
* *Dummy Answer: Furniture has the lowest performance.*

**8. Are sales increasing, decreasing, or stable?**
* *Dummy Answer: Sales are generally increasing over the observed period.*

**9. If you were a manager, which region would you prioritize?**
* *Dummy Answer: I would prioritize the East Region because it has the lowest sales and needs intervention to meet targets.*

**10. Provide one actionable recommendation based on the data.**
* *Dummy Answer: Increase inventory for "Electronics" before Q4, as historical data shows a massive spike in demand during that period.*

---

## Enhancement Section: Advanced Exploration

### Task 1: Card Visualization
*Screenshot of the Card visual showing Total Sales.*

![Card Visualization](screenshots/task1_card.png)

**Question:**
* **What is the total sales amount?**
    * *Dummy Answer: 1,250,000.00*

### Task 2: Slicer
*Screenshot showing the dashboard filtered by a specific Region using the Slicer.*

![Slicer Interaction](screenshots/task2_slicer.png)

**Questions:**
* **What happens to other visuals when you click a region?**
    * *Dummy Answer: All other charts (Pie, Line, and Bar) change to show data ONLY for the selected region.*
* **Why is filtering important in BI?**
    * *Dummy Answer: It allows users to focus on specific areas of interest (like one specific region) to find granular insights without being overwhelmed by the whole dataset.*

### Task 3: Sort Sales
*Screenshot of the Region Chart sorted by Sales Descending.*

![Sorted Chart](screenshots/task3_sort.png)

**Questions:**
* **Does sorting improve readability?**
    * *Dummy Answer: Yes.*
* **Why?**
    * *Dummy Answer: It makes it instantly clear which region is performing best and which is worst, without having to visually compare unorganized bar heights.*

### Task 4: Identify Outliers
**Questions:**
* **Which region is significantly higher or lower?**
    * *Dummy Answer: The "International" region is significantly lower than domestic regions.*
* **What might explain that difference?**
    * *Dummy Answer: Higher shipping costs or lack of brand awareness in international markets might explain the low sales.*

---

## One-Page Insight Summary

1.  **Sales Concentration:** The majority of our revenue (approx. 60%) comes from the Electronics category, indicating a high dependency on this single vertical.
2.  **Regional Disparity:** The North region outperforms the South region by 200%, suggesting a need for regional specific marketing in the South.
3.  **Growth Trend:** Overall sales are healthy with a 15% month-over-month growth rate observed in the Line Chart.
4.  **Low Performers:** The "Accessories" category has negligible sales impact and should be reviewed for potential discontinuation or bundling strategies.
5.  **Seasonal Spikes:** There is a clear sales spike at the end of the month, likely due to salary pay-cycles, which should be targeted with specific end-of-month promotions.
