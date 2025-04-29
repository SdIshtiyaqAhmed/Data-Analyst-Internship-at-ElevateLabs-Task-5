# Data-Analyst-Internship-at-ElevateLabs-Task-5

Dataset from kaggle: [sales_data.csv](https://www.kaggle.com/datasets/imranlukman/amazon-online-sales-dataset)   
Data cleaning and preprocessing: [Data-Analyst-Internship-at-ElevateLabs-Task-1](https://github.com/SdIshtiyaqAhmed/Data-Analyst-Internship-at-ElevateLabs-Task-1)   
Cleaned Dataset: [cleaned_sales_data.csv](https://github.com/SdIshtiyaqAhmed/Data-Analyst-Internship-at-ElevateLabs-Task-3/blob/main/cleaned_sales_data.csv)

Now we use cleaned_sales_data.csv for Exploratory Data Analysis (EDA) using Pandas, Seaborn, and Matplotlib modules in Python. Here is a brief overview of the process:

1. Import the required modules (i.e. Pandas, Seaborn, and Matplotlib).
2. Import the cleaned_sales_data.csv dataset.
3. If needed, perform Data Cleaning on the dataset.
4. Use various types of graphs (for example: Heatmap, Pairplot, Histogram, Boxplot, Scatterplot) available in the imported modules to visualise the data.
5. Now, explore and gather the trends, patterns and insights from the data visualisation.

## Here are some example graphs visualised using the data from the cleaned_sales_data.csv dataset:

### 1. Pair Plot with sample size of 1000:

![image](https://github.com/user-attachments/assets/7a6f87b6-4798-407d-be51-2f8342c47a37)

<b> Insights: </b> Some concentrated groups in the postal code graphs indicate that more orders are being placed from specific areas. There are a few sales, profit with products having high cost and large sales with products having low cost. There are more purchases for smaller quantities of items than for large quantities.

### 2. Heatmap:

![image](https://github.com/user-attachments/assets/75029302-4449-465a-a1ca-4da68c8b9a30)

<b> Insights: </b> There is a strong negative correlation (inverse proportionality) between profit and cost, showing that profit decreases when cost is increased. There is a strong positive correlation (proportionality) between price and profit, indicating that profit increases when cost increases. There is a positive correlation (proportionality) between quantity and sales, highlighting that when quantity increases, sales increase.

### 3. Histogram:

![image](https://github.com/user-attachments/assets/16611a9c-522f-4f13-bbf4-6a8593399fcf)

<b> Insights: </b> There are low sales that are more frequent compared to high sales, indicating that there are more orders or products that have low sales value compared to high sales value.

### 4. Boxplot:

![image](https://github.com/user-attachments/assets/89a06e08-7672-4e03-a2af-04878bc6eb9d)

<b> Insights: </b> For all the regions the 75% of sales are of lower values, which indicates that there are more low sales compared to high sales, while there are also a few outliers of high sales in each region.

### 5. Scatterplot:

![image](https://github.com/user-attachments/assets/cfdefc80-a755-478b-9fb7-e1b749e63c2b)

<b> Insights: </b> A strong negative correlation (inverse proportionality) exists between cost and profit. Sales patterns are consistent among all regions.
