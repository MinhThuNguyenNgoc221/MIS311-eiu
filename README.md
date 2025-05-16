1. Data Overview

The dataset, titled "Shoe Price", contains information on different types of shoes, including their brand, color, size, and price. It comprises 202 rows and 4 columns, representing individual shoe entries. The data likely originates from a retail or e-commerce context, where details about shoe attributes are recorded for pricing analysis or inventory management. This structured format allows for various types of analysis, including brand comparison, pricing trends by size or color, and market segmentation based on consumer preferences.

2. Data Cleaning
   
a. Missing Values
- The dataset contains missing values in the following columns:
Color: 1 missing value
Price: 1 missing value
- To handle these:
The missing color could be filled with a placeholder like "Unknown" or the most frequent color.
The missing price value should be using the mean/median price or the row removed.

b. Duplicate Rows

There were 3 duplicate rows in the dataset.
These duplicates have been removed, resulting in a cleaned dataset with 199 rows and 4 columns.

3. Descriptive Statistics
   
Insight 1: What is the distribution of shoe prices in the dataset?
![image](https://github.com/user-attachments/assets/397d2d8c-bd69-4c3f-8acb-c94074ebd0ec)

Shoe prices are mid-range:
The chart of shoe prices shows that most shoes fall within a price range of approximately $100 to $350, with the median around $210. The relatively symmetrical distribution suggests a balanced pricing strategy across the dataset. This consistency is helpful for pricing decisions and for targeting the mid-range market segment.

Insight 2: What is the distribution of shoes across different brands?
![image](https://github.com/user-attachments/assets/f312a85a-7e01-4d97-b56d-0ecbc6c219e3)

The bar chart represents that Crocs is by far the most frequently listed brand, significantly outnumbering other brands like Franco Leone and Tresmode. This indicates either a strong brand presence or popularity in the dataset, and may reflect high demand or wide availability in the current market.
