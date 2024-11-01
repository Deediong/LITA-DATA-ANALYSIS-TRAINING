# MY LITA JOURNEY -PROJECT OUTLINE

## PROJECT TOPIC: MICROSOFT EXCEL FOR DATA CLEANING, AND ANALYSIS TRAINING DOCUMENTATION

## Table of Contents
- *[Project Overview](#project-overview)*
- *[Data Sources](#data-sources)*
- *[Tools Used](#tools-used)*
- *[Data Cleaning and Preparation](data-cleaning-and-preparation)*
- *[Exploratory Data Analysis](#exploratory-data-analysis)*
- *[Data Analysis](#data-analysis)*
- *[Data Visualization](#data-visualization)*
- *[Project Documentation](#project-documentation)*


## Project Overview

 This Excel documentation aims at letting others go through what I learnt while in the Data Analysis program with LITA (Ladies In Tech Africa) at The Incubator Hub. This documentation will help you navigate through Excel like a pro.

### Data Sources

A dummy dataset was used for this analysis to demonstrate data wrangling and insight creation using data validation in Excel, Excel functions like VLOOKUP, HLOOKUP, CONCATENATE, SUM, AVERAGE, TRIM, PROPER, etc. Excel charts, Pivot tables, SQL, and Power BI. The dataset used is Excel Functions 1-Numbers, and Excel Functions 2-Texts. The data was provided in CSV format, making it accessible for analysis. The goal is to identify key trends and correlations, showcasing the effectiveness of data visualization in informing business decisions.

### Tools Used
- Microsoft Excel
    - *[Download Here](https://www.microsoft.com)*
       
      - For Data Cleaning
      - For Data Analysis
      - For Data Visualization using Pivot Tables
     
- SQL Server For Data Analysis
    - [Download Here](https://www.microsoft.com/en-us/sql-server/sql-server-downloads?)
     
- Microsoft Power BI For Creating Reports
   -  *[Download Here](https://apps.microsoft.com/detail/9NTXR16HNW1T)*

  - Git Hub For Portfolio Building
      - *[Download Here](https://desktop.github.com/download/)*

     
### Data Cleaning and Preparation
In the initial phase of the data cleaning and preparation, we performed the following actions;

   1. Data loading and Inspection: Checked for spelling errors, eliminated unnecessary spaces using trim, and proper to arrange names in the proper alphabets.
         -  =PROPER(TRIM(B6))
        
   2. Sorting: Sorted the Excel Functions 1-Numbers dataset by the Company column to organize Salary in descending order.
      
   3. Finding key statistics using Excel Functions (SUM,AVERAGE,MAX,MIN,COUNT,LARGE, and SMALL)
      - =SUM(D8:D27)
      - =AVERAGE(D8:D27)
      - =MAXIFS(D12,C12,C14)
      - =COUNTIF(C8:C27,C16)

   4. Created new columns:
      -  Transaction Category: Added a new column to catagorize high, medium, and low categories using an IF function.
      -  =IF(J2<=20,"Low",IF(J2<=50,"Medium","High"))
     
### Exploratory Data Analysis
#### Salary summary statistics

- What is the average salary?
- Who earned the highest in the company?
- What is the lowest salary?
- What is the total number of staff in the company?
- What is the total number of staff in Nasarawa?
- What is the average Oyo salary?
  
  ![image](https://github.com/user-attachments/assets/b0a26fb4-c3cc-45d5-a2e1-ecbf859b2ab7)

  		
![image](https://github.com/user-attachments/assets/fee8a433-20b5-4d46-9763-affd8e57c768)


  ### Data Analysis
  These are some of the queries I used for my analysis;
  
- SQL QUERY

 ```SQL
SELECT * FROM TABLE1
WHERE CONDITION = TRUE
```

```SQL
SELECT * FROM TABLE2
WHERE COLUMN = Names, Salary;
```

### POWER BI
 1. Data Modelling
 2. DAX Functions
 3. Create Table
 4. Create Measure
 5. Calculated Columns
 6. Conditional Formatting
 7. Data Visualization ![Power BI Dashboard](https://github.com/user-attachments/assets/368c1a1c-c695-4dca-8db2-0c3efd2cd2fb)


### Data Visualization
![Pivot Table and Chart Data](https://github.com/user-attachments/assets/eee54599-5b1a-4782-b42f-74f17636512f)

![Pivot Table](https://github.com/user-attachments/assets/8788baca-4cc7-4a76-84d8-52d2441b05b3)

![Excel Charts](https://github.com/user-attachments/assets/75ed7479-3e4b-4220-91bb-1cbb573df609)

![VLOOKUP 1](https://github.com/user-attachments/assets/2f94dc4d-bcd3-4432-8d1c-8f7195a3533b)

![VLOOKUP 2](https://github.com/user-attachments/assets/e898bb89-e27d-45b0-8b0e-ba914e27acab)

![Power BI Text Cleaning 2](https://github.com/user-attachments/assets/7301f930-894d-48e1-a1fc-699a115005f9)

![Power BI Text Cleaning 3](https://github.com/user-attachments/assets/ea07f3fe-6e9c-4f3f-aaa3-d80cd5948424)

![Power BI Text Cleaning 4](https://github.com/user-attachments/assets/178a2b1c-919f-49cf-b18d-32ca34a90707)


## Project Documentation


### Creating a github account  *[Download Here](https://desktop.github.com/download/)*
   1. Profile Update 
   2. Repository Creation
   3. Using the Markup Language
