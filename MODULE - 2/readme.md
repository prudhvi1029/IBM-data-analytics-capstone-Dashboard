# Module 2: Data Wrangling
### Overview

In this module, we clean and prepare a dataset for analysis by performing a series of data wrangling techniques. We identify and remove duplicate rows, address missing values, and normalize data to make it ready for data analysis.

### Learning Objectives

By the end of this module, you should be able to:

* Identify and remove duplicate values from a dataset.
* Handle missing values in the dataset.
* Normalize data in specific columns for consistent comparisons.

### Key Concepts

* Data Wrangling (Munging): The process of cleaning and transforming raw data into a format that can be easily analyzed.
* Duplicate Rows: Identical rows in a dataset which can cause biases in analysis.
* Missing Values: Instances where data points are not recorded. These need to be handled to maintain data integrity.
* Normalization: Standardizing data for meaningful comparisons.

### Assignment Tasks

The following tasks are covered in this module:

#### Identifying and Removing Duplicates

* Objective: Identify duplicate rows and remove them from the dataset.
* Methods: DataFrame.duplicated(), DataFrame.drop_duplicates().
  
#### Handling Missing Values

* Objective: Identify columns with missing values and impute these missing values based on specific criteria.
* Methods: DataFrame.isnull(), DataFrame.fillna().
  
#### Normalization

* Objective: Create a new column, NormalizedAnnualCompensation, to standardize compensation values across different frequencies (Yearly, Monthly, Weekly).
* Methods: DataFrame.apply() with a custom function to calculate annual compensation.

### Results and Outputs

* Final Dataframe: A cleaned and normalized dataset ready for further analysis.
* New Column: NormalizedAnnualCompensation provides annualized compensation for easy comparison
  
### Conclusion

Through the data wrangling process in Module 2, we successfully cleaned and standardized the dataset, making it suitable for analysis. We identified and removed duplicate entries to eliminate data redundancy, handled missing values to ensure completeness, and normalized the compensation data for consistent comparisons across records. These steps are critical for maintaining data quality and reliability, enabling accurate insights and analysis in subsequent stages.

By implementing these techniques, we developed a deeper understanding of data wrangling best practices, which are essential in any data analysis workflow. This prepared dataset will now serve as a foundation for more complex analyses and visualizations in the next modules.
