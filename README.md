# Data Engineering: Preprocessing & Merging data from multiple sources    

 - [Source Code and brief report](https://github.com/DataSorcerer/Data-Engineering-Preprocess-Merge-Data/blob/master/Data_Engineering_Report_and_SourceCode.ipynb)
 - [Detailed report](https://github.com/DataSorcerer/Data-Engineering-Preprocess-Merge-Data/blob/master/DataEngineering_DetailedReport.pdf)   

The identification of appropriate sources of data and its pre-processing is the integral part of any data analytics task. <font color="blue">Data wrangling</font> accounts for the most tedious and time-consuming activity in the analytics pipeline. Here, we try to collect data about *playing pitches in area around Dublin, Ireland* in various <font color="brown">heterogenous formats</font> like CSV/ XML/ KML data files and REST webservices (for geographical data).     

**Data Source:** [Open data from Irish government portal](https://data.gov.ie/)    

<b><font color="blue" size=3>Objective:</font></b>    

The aim of this task is to create a dataset that exhibits following properties:   

1.	**Complete:** Should include all relevant fields from individual dataset
2.	**Clean:** Free of discrepancies
3.	**Unique:** No duplicate records
4.	**Consistent:** Field values should be represented uniformly     

<b><font color="blue" size=3>Key Tasks performed:</font></b>    
1. **Exploratory Analysis:** Understanding data format and issues  
2. **Data Modelling:** Designing final unified data model    
3. **Data Quality Enhancement:**   
    3.1. *Data cleaning:* Handle erroneous data, outliers, duplicates and other such issues    
    3.2. *Data enrichment:* Obtain missing geographical data using geocoding from the available REST web-services   
4. **Merging:** Combine data from all the sources into a single structure that could be used for further analysis.  

<b><font color="blue" size=3>Important libraries used:</font></b>  
1. Pandas: For storing and manipulating the data in structured data frames    
2. Numpy: For statistical analysis of data    
3. ArcGIS and Geopy API for accessing related geographical web services

