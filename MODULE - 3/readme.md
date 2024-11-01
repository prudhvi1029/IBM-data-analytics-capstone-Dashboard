# MODULE - 3 :- EXPLOTARY DATA ANALYSIS (EDA)

In this module, we performed exploratory data analysis (EDA) on the cleaned dataset from Module 2. Our primary goals included examining data distribution, identifying outliers, and finding correlations among features. This analysis helped us gain further insight into the data, preparing it for modeling and in-depth analysis in future modules.

### Learning Objectives

##### In this module, we aimed to:

* Examine the distribution of data in the dataset.
* Identify outliers in key columns.
* Remove identified outliers to clean the data further.
* Recognize correlations between various numerical features.

### Key Tasks

##### 1.	Data Distribution Analysis:
* Plotted the distribution curve and histogram for the ConvertedComp column to understand its spread.
* Calculated the median of ConvertedComp, identifying a median salary value of 57,745 USD.
##### 2.	Outliers Identification:
* Used the five-number summary on the Age column to get a general understanding of its distribution.
* Created a box plot for ConvertedComp to visually identify potential outliers.
* Calculated the Interquartile Range (IQR) for ConvertedComp and used it to set upper and lower bounds.
* Found 879 outliers in ConvertedComp based on the IQR method.
##### 3.	Outliers Removal:
* Created a new DataFrame df_no_outliers by removing outliers from ConvertedComp.
* After removing outliers, the median and mean values of ConvertedComp were recalculated:
* Median: 52,704 USD
* Mean: 59,883 USD
##### 4.	Further Visualizations:
* Plotted a histogram for the Age column with custom bins for a clearer view of the data distribution.
* Examined outliers in the Age column using a box plot, identifying any data points below the Q1 value.
##### 5.	Correlation Analysis:
* Analyzed correlations between Age and other numerical columns.
* Notably found a positive correlation of 0.105 between Age and ConvertedComp, indicating a weak positive relationship.

### Results and Insights

* Identified the median and distribution of key financial and demographic features.
* Removed significant outliers to refine the dataset.
* Determined weak positive correlation between Age and ConvertedComp, indicating that age has a slight impact on compensation within this dataset.

### Conclusion

This module helped us develop a deeper understanding of the data by identifying outliers, analyzing distributions, and exploring feature correlations. These insights are crucial for making informed decisions in the subsequent analysis and modeling stages.

This README provides an overview of the EDA process, as well as instructions and key insights obtained in this module. Each step prepares the dataset for further stages, such as feature engineering or modeling.
