# Laboratory Work 1 - Introduction to Business Intelligence & Power BI

**Student Name:** Jerold M. Amora

---

## Activity Overview
**Objective:** To import CSV data into Power BI, identify dataset structures, create basic visualizations, and generate simple insights to understand how BI transforms raw data into meaningful information.

**File Used:** [LW1_Basic_Sales_Data.csv](LW1_Basic_Sales_Data.csv)

---

## Part 1 & 2: Loading Data and Interface

### Data View Verification
*Screenshot of the Data View showing all columns correctly formatted.*

**1. Default Data Types (Before Correction)**
*Screenshot showing the data types as initially loaded by Power BI.*

![Default Data Types Before Correction](screenshots/Part%201%20%26%202%20Loading%20Data%20and%20Interface/DEFAULT%20DATATYPES/DEFAULT%20DATA%20TYPES%20BEFORE%20CORRECTION_page-0001.jpg)
![Default Data Types Before Correction](screenshots/Part%201%20%26%202%20Loading%20Data%20and%20Interface/DEFAULT%20DATATYPES/DEFAULT%20DATA%20TYPES%20BEFORE%20CORRECTION_page-0002.jpg)
![Default Data Types Before Correction](screenshots/Part%201%20%26%202%20Loading%20Data%20and%20Interface/DEFAULT%20DATATYPES/DEFAULT%20DATA%20TYPES%20BEFORE%20CORRECTION_page-0003.jpg)

**2. Corrected Data Types**
*Screenshot showing the data types after manual verification and adjustment.*

![Corrected Data Types](screenshots/Part%201%20%26%202%20Loading%20Data%20and%20Interface/CORRECTIONED%20DATATYPES/DEFAULT%20DATA%20TYPES%20AFTER%20CORRECTION_pages-to-jpg-0001.jpg)
![Corrected Data Types](screenshots/Part%201%20%26%202%20Loading%20Data%20and%20Interface/CORRECTIONED%20DATATYPES/DEFAULT%20DATA%20TYPES%20AFTER%20CORRECTION_pages-to-jpg-0002.jpg)
![Corrected Data Types](screenshots/Part%201%20%26%202%20Loading%20Data%20and%20Interface/CORRECTIONED%20DATATYPES/DEFAULT%20DATA%20TYPES%20AFTER%20CORRECTION_pages-to-jpg-0003.jpg)

**Data Type Checks:**
* **Product/Sales/Category/Region/Date:** All columns are visible.
* **Date:** Formatted as DATE dataype by default.
* **Sales:** Corrected to DECIMAL NUMBER datatype (was formatted as WHOLE NUMBER datatype by default).
* **Product/Category/Region:** Formatted as TEXT datatype as default.

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
    * *Answer: The "WEST" region has the highest sales bar compared to the other regions.*

### Step 3: Sales by Category
*Screenshot of the Pie Chart showing Sales by Category.*

![Sales by Category Pie Chart](screenshots/Part%3%Creating%Auto-Generated%Visuals/part3_step3_category.png)

**Questions:**
* **Which category dominates?**
    * *Answer: The "Electronics" category dominates the chart with the largest slice.*
* **Is the distribution balanced?**
    * *Answer: No, the distribution is not balanced; "ELECTRONICS" takes up 40.82% of the chart while "OFFICE SUPPLIES" only takes up 19.99%.*

### Step 4: Sales Over Time
*Screenshot of the Line Chart showing Sales over Date.*

![Sales Over Time Line Chart](screenshots/Part%3%Creating%Auto-Generated%Visuals/part3_step4_line.png)

**Questions:**
* **Is there growth?**
    * *Answer: No, There is a clear negative growth trend. Sales decrease from approximately 0.20M in 2024 to around 0.02M in 2025, indicating a substantial year-over-year decline*
* **Any noticeable trend?**
    * *Sales seem to decline significantly at the end of every quarter.*

---

## Part 4: Basic Data Insight Interpretation

* **Which region contributes most revenue?**
    * *Answer: Based on the column chart, the WEST Region contributes the most revenue.*
* **Which product category performs best?**
    * *Answer: ELECTRONICS is the best performing category.*
* **Are sales consistent across dates?**
    * *Answer: No, sales fluctuate. There are peaks in the middle of the month and dips at the start.*
* **What business recommendation can you suggest?**
    * *Answer: Since the WEST Region is performing well, we should investigate their marketing strategy and apply it to the lower-performing NORTH Region.*

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
* *Answer: The West Region.*

**7. Which category has the lowest performance?**
* *Answer: Office supplies has the lowest performance.*

**8. Are sales increasing, decreasing, or stable?**
* *Answer: Sales are generally decreasing over the observed period.*

**9. If you were a manager, which region would you prioritize?**
* *Answer: I would prioritize the North Region because it has the lowest sales and needs intervention to meet targets.*

**10. Provide one actionable recommendation based on the data.**
* *Answer: Increase inventory for "Electronics", as historical data shows a massive demand for this category.*

---

## Enhancement Section: Advanced Exploration

### Task 1: Card Visualization
*Screenshot of the Card visual showing Total Sales.*

![Card Visualization](screenshots/Enhancement%Section:%Advanced%Exploration/task1_card.png)

**Question:**
* **What is the total sales amount?**
    * *Answer: 220,229*

### Task 2: Slicer
*Screenshot showing the dashboard filtered by a specific Region using the Slicer.*

![Slicer Interaction](screenshots/Enhancement%Section:%Advanced%Exploration/task2_slicer.png)

**Questions:**
* **What happens to other visuals when you click a region?**
    * *Answer: All other charts (Pie, Line, and Bar) change to show data ONLY for the selected region.*
* **Why is filtering important in BI?**
    * *Answer: It allows users to focus on specific areas of interest (like one specific region) to find granular insights without being overwhelmed by the whole dataset.*

### Task 3: Sort Sales
*Screenshot of the Region Chart sorted by Sales Descending.*

![Sorted Chart](screenshots/Enhancement%Section:%Advanced%Exploration/task3_sort.png)

**Questions:**
* **Does sorting improve readability?**
    * *Answer: Yes.*
* **Why?**
    * *Answer: It makes it instantly clear which region is performing best and which is worst, without having to visually compare unorganized bar heights.*

### Task 4: Identify Outliers
**Questions:**
* **Which region is significantly higher or lower?**  
    * **Answer:** The **North** region is significantly lower compared to the other regions (West, East, and South). While West (~59,041), East (~58,411), and South (~56,793) have relatively similar sales figures, North (~45,984) falls noticeably below this range, making it the clear lower outlier.
* **What might explain that difference?**  
    * **Answer:** The lower sales in the North region may be due to factors such as a smaller customer base, lower market penetration, reduced marketing efforts, stronger competition, or logistical and distribution challenges within that region.


---

## One-Page Insight Summary

1. **Top Categories:** Electronics is the best-selling category with roughly 41% of sales, but Furniture is very close behind at 39%.
2. **Lowest Performing Category:** Office Supplies has the lowest performance, contributing only about 20% to the total revenue.
3. **Best Region:** The West region contributes the most to sales (approx. 59k), followed closely by the East and South regions.
4. **Regional Lag:** The North region has the lowest sales (46k) compared to the other three regions which are all above 56k.
5. **Yearly Trend:** The line chart shows a sharp drop in sales volume from 2024 (202k) to 2025 (17k), suggesting incomplete data for the new year or a significant drop in activity.
