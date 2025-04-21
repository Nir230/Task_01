# Task_01

In our data cleaning process, we started by handling missing values, deciding whether to remove or fill in gaps using methods like .dropna() and .fillna(). Next, we removed duplicate records to ensure that no data was being counted twice, using .drop_duplicates(). We also standardized text values, making sure things like country names and other categorical data were consistent, fixing issues like capitalization or variations in names. For date handling, we converted all inconsistent date formats to a uniform dd-mm-yyyy format using pandas' .to_datetime() function. We checked and fixed data types, ensuring columns like release_year were correctly converted to integers and date_added to a proper datetime format. Lastly, we handled inconsistent data formats and ensured everything in the dataset was uniform and easy to work with, making the data cleaner and ready for further analysis. These steps ensure that the dataset is accurate, consistent, and structured in a way that will allow for meaningful analysis.

# Questions
1. What are missing values and how do you handle them?
   
Missing values are gaps in your data where information is missing. You can handle them by either removing rows or columns with missing values using .dropna() or filling in the gaps with a placeholder or calculated value using .fillna().

2. How do you treat duplicate records?
   
Duplicate records are when the same data appears more than once. You handle them by removing the extra copies using .drop_duplicates() to ensure your data is not counted multiple times.

3. Difference between dropna() and fillna() in Pandas?
  
dropna() removes rows or columns with missing values.
fillna() fills missing values with something else (like the average value or a placeholder).

4. What is outlier treatment and why is it important?

Outliers are values that are much higher or lower than the rest of the data. Treating outliers means deciding whether to remove or adjust them because they can distort your analysis and lead to incorrect conclusions.

5. Explain the process of standardizing data.
   
Standardizing data means making everything uniform. For example, ensuring all text is lowercase, dates are in the same format, and values are consistent (like using the same units).

6. How do you handle inconsistent data formats (e.g., date/time)?
   
Inconsistent data formats happen when the same data is written in different ways. To fix this, you convert everything into a single format, like making all dates the same (e.g., dd-mm-yyyy).

7. What are common data cleaning challenges?
    
Common challenges include handling missing data, removing duplicates, fixing inconsistent formats (like dates), dealing with outliers, and merging data from different sources with different structures.

8. How can you check data quality?
    
You check data quality by looking for missing values, duplicates, errors in formats, and making sure all data is consistent. You can also run basic checks to spot any unusual or incorrect values.
