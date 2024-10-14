## LITA_CLASS_Documentation
This is where I documented my first project while learning Data Analysis with the  Incubator Hub.

### Outline
1. [Data Cleaning and Preparations](data-cleaning-and-preparations)

[Tools Used](tools-used)

[Data Analysis](data-analysis)


---

  1. Data cleaning
  2. Data Analysis
  3. Data Visualization
     
-SQL

-Github for Portfolio Building

---
## Data Cleaning and Preparations

### Overview:
This project involves cleaning and preparing a set of data for analysis. Data cleaning is used to prepare raw,unstructured,or inconsistent data into a usable ,organized and reliable format for analysis, reporting or further processing.

### Tools Used
-Microsoft excel [Download Here](https://www.microsoft.com/en-ng/)

### Procedure

1. Data loading and Inspection: The data from the source was downloaded and loaded into Excel spreadsheet for inspection. Afterwhich, the Data was inspected for errors such as typographical erors and inconsistencies such as differencies in formats. In a set of Data for the Scheduled Pioneeer Staff of a Company, we were able to eliminate the unneccessary spaces and adjust the text format using the ```=UPPER ```, ```=LOWER```, ```=PROPER``` .and ```=TRIM``` functions. We also used the stated functions to generate a table containing the first names and surnames alone and we the use of ```=CONCATENATE```, we were able to generate the email addresses of each of the staff of the organization using their first names.
   
2. Handling missing variables: We identified some missing records (Department Code, Purchase Date Code and Asset Category Code) in a set of Data for Asset Schedule. However, we used the ```=LEFT ``` , ```=RIGHT ``` , ```=MID ``` ,```=FIND ``` and ```=SEARCH ``` functions to extract the Data from the 'Codes' Column. Also, we were able to LookUp the values of the salary allowances of each staff of the organization from the Salary Structure Worksheet using the ```=VLOOKUP``` and ```=HLOOKUP```functions.
   
4. Data cleaning and formatting

### Data Analysis

``` SQL
SELECT * FROM TABLE1 WHERE CONDITION = TRUE
```

|Heading1|Heading2|
|--------|--------|
|Table1|Table2|
