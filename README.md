# Flight-Cancellation-Data-
An analysis has been performed on a Flight cancellation dataset, focusing mainly on data wrangling techniques using Python libraries like pandas, matplotlib and seaborn.
Dataset Overview:
The dataset provides a comprehensive record of flight cancellations and delays in the United 
States, covering the years 2019 to 2023, with over 1.04m entries. Each entry captures various 
attributes related to flight details, reasons for delays, and associated factors.
Link to dataset csv file (https://drive.google.com/file/d/16n1yXHEQjFdtwy_m2jXk05-vEkTlTweT/view?usp=sharing)
Here are the questions related to the dataset I seek to answer:

**Handling missing values**
Q1. Create three variables namely Flight_Num, Flight_Cat and Flight_Full to represent 
respectively, the numerical, categorical and Full variables. Write scripts to separately load 
and execute each of the three variables created: Flight_Num, Flight_Cat and Flight_Full.
Further, describe the shape in each of the three variables.
Q2. Identify and describe the variable types in Flight_Full and report on any inconsistencies or 
unexpected data types, if any.
Q3. Investigate the presence of missing values in the Flight_Full dataset. Report both the count
and mean of missing values observed in the attributes having missing values.
Q4. How does the presence of missing data in a dataset impact the overall analysis, and what 
strategies can be employed to handle these missing values effectively? Provide an 
explanation.
Q5. Drop all columns that have missing values in the Flight_Full dataset.
Q6. The attribute CANCELLATION_CODE in the dataset contains multiple datatypes, split this 
into two distinct attributes. 
Q7. Show the distribution of the DEST_CITY_NAME as well as the ORIGIN_CITY_NAME 
attributes.
Q8. Determine if any association exists between CRS_DEP_TIME, DEP_TIME, TAXI_OUT, 
WHEELS_OFF and DEP_DELAY. Perform a similar assessment for WHEELS_ON,
TAXI_IN, CRS_ARR_TIME, DISTANCE, ARR_DELAY Critically explain the relations 
between each pair.
**Imputation**
Q9. Explain the concept of imputation in data wrangling and mention some of the techniques used 
in imputing data.
Q10. Perform separately, a mean, median and mode imputation on the top three attributes with 
the most missing values.
Q11. Write a CSV file from the resulting MEAN imputation
Outlier Analysis
Q12. Explore all the numerical variables in search of outliers. Use both descriptive statistics and 
appropriate charts to detect the presence of outliers in the various attributes.
Q13. Use the inter quartile range methodology to treat (remove) outliers from two of the attributes 
that contain outliers.
**Encoding, Discretization and Imbalance**
Q14. The attributes DELAY_DUE_CARRIER, DELAY_DUE_WEATHER, 
DELAY_DUE_NAS, DELAY_DUE_SECURITY, and DELAY_DUE_LATE_AIRCRAFT 
are observed to have so many unique values. Assuming you want to effectively address this 
challenge, determine which of these approaches: ‘feature removal’, ‘binning’, ‘frequency 
based-based encoding’ is most suitable to handle the problem. Correct the attributes based 
on the chosen method. 
Q15. The objects ‘DELAY_DUE_WEATHER’, ‘DELAY_DUE_SECURITY’, 
‘DELAY_DUE_LATE_AIRCRAFT’, ‘DELAY_DUE_NAS’ all show significant imbalances 
in the classes. Correct this anomaly in the dataset.
Q16. Provide a visualization of the up-sampled and down-sampled objects pertaining to Q13.
Q17. Consider the following objects ‘DEP_DELAY’, ‘TAXI_OUT’, ‘TAXI_IN’, and 
‘ARR_DELAY’ and perform an appropriate feature scaling for each.
Q18. Show a visualization of an estimate of the most DISTANCE travelled by the airlines
