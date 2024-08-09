# Holiday Sales
![dashboard](https://github.com/user-attachments/assets/588b776c-168d-4f56-b6b6-d6bc2e632f1a)


## Table of content

- [Data Source](#data-source)
- [Data Cleaning and Preparation](#data-cleaning-and-preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Conclusion and Recommendation](#conclusion-and-recommendation)
- [Limitation](#limitation)

## Data Source:

Dataset was gotten from kaggle.com

## Data cleaning and Preparation:

- Changed incorrect data types
- Removed duplicates and white spaces
- Formatted date
- Grouping of stores by their sizes
- A bin was created for economic indicators, Fuel price, temperature etc.

## Exploratory Data Analysis:

Objective of EDA is to answer particular quesstions such as;

1. Historical Sales Trends:

- How have the weekly sales trended over time for each store and department?
- Are there noticeable seasonal patterns in the sales data?

2. Sales Prediction:

- Can we predict the weekly sales for each department in each store for the following year?

3. Holiday Impact:

- How do holiday weeks impact sales compared to non-holiday weeks?
- Which holidays have the most significant effect on sales, and which departments are most affected?

4. Temperature Influence:
- What is the relationship between regional temperature and sales?
- Do certain departments experience more significant sales fluctuations based on temperature changes?

5. Fuel Price Impact:
- How do regional fuel prices correlate with sales figures?
- Does a rise or fall in fuel prices affect customer purchasing behavior?

6. Economic Indicators:
- How do economic indicators like CPI and unemployment rates influence sales?
- Are there particular departments or stores more sensitive to changes in these economic indicators?

7. Store Type and Size Analysis:

- How do sales vary by store type and size?
- Are larger stores or specific types of stores (e.g., urban vs. rural) more successful?

8. Top-Performing Stores:

- Which stores consistently achieve the highest sales, and what factors contribute to their success?
- Can we identify common characteristics of top-performing stores?

From the analysis of this dataset, the following responses can be derived;

- It is very noticeable that there is usually a surge in sales same time every year around week 48 and week 52, a deep is also noticeable at week 49 and 53 of every year.

![weekly sales for 2010,11 and 12](https://github.com/user-attachments/assets/6a551da7-e3a2-4cac-979c-06530c60ee49)


- Holiday weeks generally have significant impact on sales. Holiday weeks have the higher record on sales.

![holiday impact on sales](https://github.com/user-attachments/assets/d27231d0-f492-4c79-a39a-d07c29eac5aa)


- Chrismas has the most significant effect on sales, returning the highest revenue ever amongst all the weeks.

![sales made in holidays](https://github.com/user-attachments/assets/33d49260-e968-4b7d-9fc4-4259310dd34f)


- Department 7 is the most affected amongst all the department. This department has the highest sales on holidays.

![department 7](https://github.com/user-attachments/assets/48d37092-562b-425a-98ca-7c48587b91ca)


- Temperature, Fuel price, CPI and unemployment rates have no visible effect on sales.

![weekly sales by temperature,cpi, fuel price, unemployment](https://github.com/user-attachments/assets/42bc0974-43de-4bea-a0dd-dc36af962af4)


- Stores large in size do better with sales, a common characteristics.

![weekly sales by store size](https://github.com/user-attachments/assets/aa98c571-72d2-4e8b-8d3b-9c46ef658a4e)


- Store 20 achieved the highest sales, it's size contributing to it's success.

![stores performance](https://github.com/user-attachments/assets/2f655b84-be4a-4f0c-86e8-3d16b3057b0a)


## Conclusion and Recommendation:
- It can be inferred from the analysis that holiday helps boost sales. During holiday weeks, more efforts should be made to maximize profits, eg Discounts.
- Since size is a significant factor to the success of a store, the size of smaller shops should be increased.
- Departments with low sales should be looked into.
- To maximize the effect of holiday weeks, preparations should be made ahead including restocking and promotional Ads. 

 
## Limitation:
Several missing values in markdown data. Missing values are originally denoted with NA in the dataset, affecting any analysis on markdown data(in this case, any analysis involving markdown data was omitted).
