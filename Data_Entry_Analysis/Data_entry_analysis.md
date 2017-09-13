# Assignment Data Entry Analysis
### Files associated with this Assignment-
* [zoop - temp-main.xlsx](https://github.com/vrahangdale/ISQA-8086/blob/master/Data_Entry_Analysis/zoop%20-%20temp-main.xlsx)
* [zoop - temp](https://github.com/vrahangdale/ISQA-8086/blob/master/Data_Entry_Analysis/zoop%20-%20temp.xlsx)
* [pond2010](https://github.com/vrahangdale/ISQA-8086/blob/master/Data_Entry_Analysis/pond2010.xlsx)

#### Task #1: Based on our class readings, prior experience, and your own good sense, list some of the problems in the way that the data are currently organized (there are at least 8 problems with these spreadsheets; try to identify as many as possible, but at least 4).

#### **#Solution -** Some of the problem with the data organization/entry are-

1.	The species data is not organized properly like the species name in 2010 data is in row and in 2011 data are in column. They should be consistently stored either in column or rows. Column wise entry would be efficient as we can better visualize the data by just taking the column rather than providing the row number if it is stored in row wise.
2.	In 2010 data, the depth is specified as 'z' which should be properly named as depth for better consistency among various data sets. Also, the unit of depth should be entered in column name.
3.	The data doesn’t have any record of time. For the study the investigators wanted to examine the day-night distribution of 2 species of zooplankton across multiple years since time of observation is not present this can lead to an incomplete data analysis.
4.	In 2010 data, the density unit in not entered like #/L or #/mL. It should be required for the data to be consistence.
5.	There are some negative values in 2011 data in column Chippo #/L which is not right as we are counting the number of chippo/liter this must be greater than or equal to zero but negative values are allowed.
6.	The in 2010 data the column colony diameter is same as colony size in 2011 data. So, it should be named in a consistence manner. Also, there is no unit for colony size or colony diameter.
7.	There is a column named Chla in 2011 data which is not defined and is not considered in the study in 2010.
8.	The temperature data is not entered for 18-06-2010 in 2010 data and 07-06-2011 in 2011 data which can be an issue for data analysis but can be neglected as missing data.
9.	The values for Chippo #/L, Chippo ColonySize and Chla columns on date 07-06-2011 and 09-06-2011 in zoop-temp-main.xlsx are entered as random numbers which are not actual values. These values can lead to false data analysis. Moreover, in zoop-temp.xlsx file station B is mentioned which is not referenced anywhere.
10. There are some values marked in red. What does this values signifies it is not mentioned in the data set. Also there is no Reference for date like is it in dd/mm/yy or mm/dd/yy format.

#### Task #2: Suggest a new system for organization. Create a table in your Markdown document showing a potential template for later years of data collection that would address the problems you identified in #1.

#### **#Solution -**
1. Each species are specified in column name like Cuni, Chippo, Chla.
2. The Depth column is specified with unit in meter.
3. Time Column can be added with a standard unit such as UTC.
4. Density column with unit can be added.
5. Reference column can be added for any added inoformation such as station B Max and Min depth.
6. If unit of measurement are not given in column name, then a data dictionary should be provided to summarize the unit of all columns.
7.	The tables can be created for each species separately like Cuni and Chippo can have their own table with its data. Although it would be beneficial for large data set only.


### Following is the updated Table organization-

### #**_Table_**-

| Date | Depth(m) | Time | Cuni #/L | Cuni ColonySize(m) | Chippo #/L | Chippo ColonySize(mm) |  Chla #/L | Chla Colony Size(mm) | Temp | References |
|------|----------|------|----------|--------------------|------------|----------------------|-----------|---------------------|------|------------|

##### Author -
Vaibhav Rahangdale
