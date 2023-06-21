# Ukraine-Car-Sales-2019-Data-Analysis

**Note**: Please use **Excel 365** to explore this project to ensure all the formulae used in this project are availabe.

Dataset size: 9.5k rows, 10 columns

Link to the dataset: https://www.kaggle.com/datasets/swatikhedekar/eda-on-car-sales-dataset-in-ukraine

Summary of my findings:

### Data Acquisition:
Downloaded the dataset from **Kaggle**.

### Data Preprocessing:
1) Rectified spelling errors in the **Cars** col using the "Find and Replace All" method.
2) Missing values in the **Price**, **Mileage** and **Engine_Vol** cols were replaced with the median values in each of these cols for each car.
3) Missing values in the **Drive** col were safely removed as they accounted for only 5% of the data and were not associated with the insights.

### Data Analysis:
1) Created a dynamic drop-down menu that allowed for the calculation of summary statistics and correlation coefficients.
2) Utilized pivot tables to analyze multiple attributes simultaneously.
3) Categorized prices based on significant positive skewness.

### Insights:
1) Mercedes-Benz, BMW, and Toyota were the top revenue generators and also had the highest number of cars sold.
2) Crossovers generated the highest revenue, closely followed by sedans.
3) Petrol was the most common engine type among the car sales.
4) A significant portion of the cars sold fell within the $10k-$30k price range.

### Conclusion:
Customers are likely to buy a car that is either a crossover or sedan within the $10k-$30k range. Other attributes play a secondary role. The dominance of Mercedes-Benz, BMW, and Toyota in the market can be attributed to their production of high-selling crossovers and sedans within this price range.
