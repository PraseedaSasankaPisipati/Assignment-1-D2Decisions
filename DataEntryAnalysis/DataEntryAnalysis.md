###### This markdown document is describes the files,problems indentfied and suggested solutions for the Data Entry Analysis assignment.

### Title
Data Entry Analysis

### List Of Files Added In Data Entry Analysis Directory


## Authors

**Praseeda Sasanka Pisipati** - *Initial work* - [Praseeda Sasanka Pisipati](https://github.com/PraseedaSasankaPisipati)

See also the list of [contributors](https://github.com/PraseedaSasankaPisipati/Assignment-1-D2Decisions/graphs/contributors) who participated in this project.

### Summary Of The Files

The 3 files added as a part of this assignment belong to the same research – the aquatic scientists who collected the above data wanted to examine the day-night distribution of 2 species of zooplankton across multiple years. The type of zooplankton they studied is called rotifers generally, and specifically the genus Conochilus, in which groups of individual rotifers stick together in colonies. The scientists plan to repeat this study for several more years. 

### Task 1 Problems Identification

#1: Based on class readings, prior experience, and your own good sense, list some of the problems in the way that the data are currently organized (there are at least 8 problems with these spreadsheets; try to identify as many as possible, but at least 4.

**Answere:** 

The following are the problems identified from the data files provided in this assignment:
1. Incomplete Data - Timings are not noted for the data, which will not allow the user to analyze the data by the criteria of the day and night distribution
2. Insufficient parameters - In the graph, the y-axis parameter is not mentioned
3. Insufficient/Inconsistent Data - The units of measurement of the data is not mentioned
4. No comparision between the data - The pond data is collected in 2010, while the zoop data is collected in 2011
5. No yellow notebook provided for the map and details
6. Data Redundancy - Same data is collected and maintained in two different files when all the columns are same in both zoop-temp and zoop-temp-main files
7. No Restricitons on data collected - Negative values cannot be possible for the number of cuni/chippo per litre
8. Inconsistent column names - Some oft he column names are abbreviated and are not defined in all the excel sheets provided. The user cannot get a clear idea on what exactly these columns mean.
9. Confusing colour coding for data - Few values of data are in red/yellow.Reason for these color codes is not mentioned.

### Task 2 Solutions

#2: Suggest a new system for organization. Create a table in your Markdown document showing a potential template for later years of data collection that would address the problems you identified in #1.

#### **Answere**:

1. Single file is sufficient for the data in zoop-temp.xlsx and zoop-temp-main.xlsx files can be combined into one single excel sheet
2. Time needs to be noted for the data . This can be done under a new column "Time". This can be used to analyze the data by day and night distribution.
3. A new column with the name "Location" can be added  where a link to the map can be provided. Another additional column can be added with the name as "MetaData Information" for noting any other important details
4. All the units of measurement needs to be included in the column names so that the user can easily identify the data being recorded.
5. Combining all the three excel files into one single file can help in eliminating these discepancies
6. Data restrictions needs to be enforced in order to eliminate the risk of negative values being stored.
7. No abbrevations should be allowed in defining the column names. Standard naming conventions should be followed while defining the column names. This allows the uniformity in defining the future columns if anything new needs to added. Abbrevations can be defined in the "MetaData Information" column.
8. Unncecessary colour coding of the data can be removed.

### Proposed Tables 

**Table 1:**  

| Date | Time(CST) | Temperature(Degree Fahrenheit) | Density(Liters) | Colony Diameter(meters) | Species | Depth(meters) | Chippo #/L | Chippo Colony Size(millimeter) | Chlorophyll A | Station | Miscellaneous Information |
|------|-----------|-----------------------------|-----------------|-------------------------|---------|---------------|------------|--------------------------------|---------------|---------|---------------------------|
|      |           |                             |                 |                         |         |               |            |                                |               |         |                           |

**Table 2:**  

| Date | Time(CST) | Temperature(Degree Fahrenheit) | Density(Liters) | Colony Diameter(meters) | Species | Depth(meters) | Cuni #/L | Cuni Colony Size(millimeter) | Chlorophyll A | Station | Miscellaneous Information |
|------|-----------|-----------------------------|-----------------|-------------------------|---------|---------------|----------|------------------------------|---------------|---------|---------------------------|
|      |           |                             |                 |                         |         |               |          |                              |               |         |                           |

## Last modified by
    Praseeda Sasanka Pisipati

## Last modified at
   09/011/2017 08:40 PM 
