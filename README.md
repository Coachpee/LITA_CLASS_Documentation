## LITA_CLASS_Documentation
This is where I documented my first projects while learning Data Analysis with the  Incubator Hub.

---
### Outline

### 1. Basic Excel Functions and Pivot Table

- [Data Cleaning and Preparations](data-cleaning-and-preparations)

- [Data Analysis](data-analysis)
   
- [Data Visualization](data-visualization)
     
### 2. SQL

### 3. Power BI
---
### 1. Basic Excel Functions and Pivot Table

### Overview:
This project involves cleaning and preparing a set of data for analysis. Data cleaning is used to prepare raw,unstructured,or inconsistent data into a usable ,organized and reliable format for analysis, reporting or further processing.

### Tools Used
-Microsoft excel [Download Here](https://www.microsoft.com/en-ng/)

### Procedure

#### A. Data Cleaning and Preparation

1. DATA LOADING AND INSPECTION: The data from the source was downloaded and loaded into Excel spreadsheet for inspection. Afterwhich, the Data was inspected for errors such as typographical erors and inconsistencies such as differencies in formats. In a set of Data for the Scheduled Pioneeer Staff of a Company, we were able to eliminate the unneccessary spaces and adjust the text format using the ```=UPPER ```, ```=LOWER```, ```=PROPER``` .and ```=TRIM``` functions. We also used the stated functions to generate a table containing the first names and surnames alone and we the use of ```=CONCATENATE```, we were able to generate the email addresses of each of the staff of the organization using their first names.
   
2. HANDLING MISSING VARIABLES: We identified some missing records (Department Code, Purchase Date Code and Asset Category Code) in a set of Data for Asset Schedule. However, we used the ```=LEFT ``` , ```=RIGHT ``` , ```=MID ``` ,```=FIND ``` and ```=SEARCH ``` functions to extract the Data from the 'Codes' Column. Also, we were able to LookUp the values of the salary allowances of each staff of the organization from the Salary Structure Worksheet using the ```=VLOOKUP``` and ```=HLOOKUP```functions.

#### B. Data Analysis

With the use of some Basic Excel Functions such as ```=SUM```, ```=AVERAGE``` , ```=MAX```, ```=MIN```,```-LARGE``` and ```=SMALL``` we were able to carry out some calculations to determine the total salaries, average salaries, maximum, minimum, nth highest and nth smallest salaries respectively. Also, using the 'Ifs' functions (SUMIFs,MAXIFs,MINIFs,and AVERAGEIFs) we were able to carry out some calculations for specific companies.

#### C. Data Visualization

Here we used Pivot table to cre

``` SQL
SELECT * FROM TABLE1 WHERE CONDITION = TRUE
```

|Heading1|Heading2|
|--------|--------|
|Table1|Table2|
