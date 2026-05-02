# MIST4610-project2

# Team Information
Hailey Brakke (https://github.com/haileybrakke/MIST4610-project2)

Will Federer (put link here)

Summer Sayedzada (put link here)

Tony Jimenez (put link here)

Ja’Khiyan Dowdy (put link here)

# Our Dataset

The dataset used for this analysis is the U.S. Chronic Disease Indicators dataset, obtained from Data.gov and originally compiled by the Centers for Disease Control and Prevention (CDC). This dataset provides comprehensive, state-level data on a wide range of chronic health conditions and risk factors across the United States. The dataset has 34 columns and over 300,000 rows. Data can be analyzed across several dimensions, including time (year), geography (state), health condition (indicator), and demographics. 

Key Columns and Data Types:  
Year (Numerical): The year data was collected   
Location (String): The U.S. state where data was collected   
Question (String): Describes the specific health indicator being measured  
Data Value (Numerical): The number associated with the specific health indicator   
Data Value Unit (String): Specifies the unit of measurement 
Stratification Category (String): Collects demographic information   
Stratification (String): Collects more specific demographic breakdowns within the category   
Geolocation (Geographic values): Specifies the exact location data was collected   


# Question 1

How have cancer rates changed over time across U.S. states, and which regions consistently experience the highest burden?   
Importance: Evaluating how cancer rates change over time and which areas are suffering the most is important from social and economic perspectives. From a social standpoint, regional differences in cancer burden may reflect disparities in healthcare access, environmental quality, and socioeconomic conditions. Understanding these patterns helps highlight populations that may be underserved or at greater risk. From an economic perspective, understanding how rates are changing over time will help evaluate the success of public health initatives and investments in overall healthcare infrastructure. This relates to the dataset's cancer-related indicators which include information on the over multiple years and multiple regions of the United States.

# Question 2

What is the relationship between key behavioral risk factors (smoking, physical inactivity, and dietary habits) and cancer incidence across U.S. states?    
Importance: xxxxxx

# Manipulations Applied to Dataset

Question 1:    
To answer Question 1, the team perfomed several manipulations to the dataset. First, the team removed unnessecary colums to clean the data. Those include columns such as demographic data, data value footnotes, low confidence limit, high confidence limit, data source, and more. This narrowed down the dataset to 8 columns: Year Start, Year End, Location (State), Question, Data Value Unit, Data Value Type, Data Value, and Geolocation. After narrowing the columns, the team filterd the Question, Data Value Unit, and Data Value Type. The team filtered Question to specify "Invasive cancer (all sites combined), incidence", Data Value Unit to "per 100,000", and Data Value Type to "Age-adjusted Rate". Finally, the team removed rows where Data Value was null or empty. This allowed the team to ensure that all visualizations were based on data of the same unit and type as well as to ensure complete and reliable data.

# Question 1 Analysis

# Question 2 Analysis


