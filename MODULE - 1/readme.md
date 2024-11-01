#  Module 1: Data Collection and Exploration

### Project Overview

In Module 1 of the IBM Data Analyst Capstone Project, we focused on gathering and exploring data, essential first steps in data analysis. This module involved collecting job-related data through APIs, scraping web pages, and conducting preliminary exploration of a survey dataset that provides insight into the technical and professional experiences of developers globally.

### Learning Objectives

In this module, we aimed to:

* Familiarize ourselves with HTTP requests and responses.
* Collect job-related data using APIs and store it in a structured format.
* Perform web scraping using Python’s BeautifulSoup to gather data from web pages.
* Conduct initial data exploration to understand the structure of the survey dataset.

### Key Tasks

##### 1. Data Collection

* API Interaction: Queried job postings filtered by technology and location using the requests library.
* Data Storage: Stored job data retrieved from APIs in Excel spreadsheets (job-postings.xlsx and jobpostings_technologies.xlsx).

##### 2. Web Scraping

* HTML Parsing: Downloaded web pages using the requests library and parsed content with BeautifulSoup.
* Data Extraction:
* Collected all links on a web page.
* Retrieved URLs for all images.
* Scraped tabular data from HTML tables.

##### 3. Survey Dataset Exploration

* Data Loading: Loaded the dataset from an IBM Cloud URL into a DataFrame.
* Dataset Shape: Discovered the dataset has 11,552 rows and 85 columns.
* Column Types: Analyzed data types to identify numerical, categorical, and text data.
* Descriptive Analysis:
* Calculated the mean age of survey respondents.
* Found 135 unique countries and listed all unique country names.

### Results and Insights

* Collected and stored job data, categorized by technology and location, in Excel files.
* Successfully downloaded and parsed HTML content to extract links, images, and tables.
* Gained a preliminary understanding of the survey dataset, including key statistics on age and country demographics.

### Conclusion

Module 1 established foundational skills for data acquisition, storage, and initial exploration. These skills are critical for preparing datasets and gathering additional information that will be used in future modules for deeper analysis and modeling.
