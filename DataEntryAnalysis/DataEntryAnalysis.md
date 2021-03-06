###### This markdown document is describes the files,problems indentfied and suggested solutions for the Data Entry Analysis assignment.

### Title
Data Entry Analysis

### List Of Files Added In Data Entry Analysis Directory
1. [POND2010](https://github.com/PraseedaSasankaPisipati/Assignment-1-D2Decisions/blob/master/DataEntryAnalysis/pond2010.xlsx)
2. [ZOOPTEMP](https://github.com/PraseedaSasankaPisipati/Assignment-1-D2Decisions/blob/master/DataEntryAnalysis/zoop%20-%20temp-main.xlsx)
3. [ZOOPTEMP-MAIN](https://github.com/PraseedaSasankaPisipati/Assignment-1-D2Decisions/blob/master/DataEntryAnalysis/zoop%20-%20temp.xlsx)


## Authors

**Praseeda Sasanka Pisipati** - *Initial work* - [Praseeda Sasanka Pisipati](https://github.com/PraseedaSasankaPisipati)

See also the list of [contributors](https://github.com/PraseedaSasankaPisipati/Assignment-1-D2Decisions/graphs/contributors) who participated in this project.

### Summary Of The Files

The 3 files added as a part of this assignment belong to the same research – the aquatic scientists who collected the above data wanted to examine the day-night distribution of 2 species of zooplankton across multiple years. The type of zooplankton they studied is called rotifers generally, and specifically the genus Conochilus, in which groups of individual rotifers stick together in colonies. The scientists plan to repeat this study for several more years. 

### Task 1 Question

#1: Based on class readings, prior experience, and your own good sense, list some of the problems in the way that the data are currently organized (there are at least 8 problems with these spreadsheets; try to identify as many as possible, but at least 4.

**Answer:** 

The following are the problems identified from the data files provided in this assignment:
1. Incomplete Data - Timings are not noted for the data, which will not allow the user to analyze the data by the criteria of the day and night distribution
2. Insufficient parameters - In the graph, the y-axis parameter is not mentioned
3. Insufficient/Inconsistent Data - The units of measurement of the data is not mentioned
4. No comparision between the data - The pond data is collected in 2010, while the zoop data is collected in 2011
5. No yellow notebook provided for the map and details
6. Data Redundancy - Same data is collected and maintained in two different files when all the columns are same in both zoop-temp and zoop-temp-main files
7. No Restricitons on data collected - Negative values cannot be possible for the number of cuni/chippo per litre
8. Inconsistent column names - Some of the column names are abbreviated and are not defined in all the excel sheets provided. The user cannot get a clear idea on what exactly these columns mean.
9. Confusing colour coding for data - Few values of data are in red/yellow.Reason for these color codes is not mentioned.

### Task 2 Suggested Solutions

#2: Suggest a new system for organization. Create a table in your Markdown document showing a potential template for later years of data collection that would address the problems you identified in #1.

#### **Answer**:

1. Single file is sufficient for the data in zoop-temp.xlsx and zoop-temp-main.xlsx files can be combined into one single excel sheet
2. Time needs to be noted for the data . This can be done under a new column "Time". This can be used to analyze the data by day and night distribution.
3. A new column with the name "Location" can be added  where a link to the map can be provided. Another additional column can be added with the name as "MetaData" for noting any other important details
4. All the units of measurement needs to be included in the column names so that the user can easily identify the data being recorded.
5. A single file can replace the existing 3 files which will eliminate data redundancy and increase data integrity.
6. Data restrictions needs to be enforced in order to eliminate the risk of negative values being stored.
7. No abbrevations should be allowed in defining the column names. Standard naming conventions should be followed while defining the column names. This allows the uniformity in defining the future columns if anything new needs to added. Abbrevations can be defined in the "MetaData" column.
8. Unncecessary colour coding of the data can be removed.

### Proposed Tables 

**Table 1 for station A:**  

| Time(CDT) | Date | Cuni #/L | Cuni Colony Size(millimeter) | Species | Depth(meters) | Chippo #/L | Chippo Colony Size(millimeter) | Chlorophyll A | Station | Density(Liters) | Temperature(Degree Fahrenheit) | MetaData |
|-----------|------|----------|------------------------------|---------|---------------|------------|--------------------------------|---------------|---------|-----------------|--------------------------------|----------|

**Table 2 for station B:**  

| Time(CDT) | Date | Cuni #/L | Cuni Colony Size(millimeter) | Species | Depth(meters) | Chippo #/L | Chippo Colony Size(millimeter) | Chlorophyll A | Station | Density(Liters) | Temperature(Degree Fahrenheit) | MetaData |
|-----------|------|----------|------------------------------|---------|---------------|------------|--------------------------------|---------------|---------|-----------------|--------------------------------|----------|

## Last modified by
    Praseeda Sasanka Pisipati

## Last modified at
   09/011/2017 08:40 PM 
