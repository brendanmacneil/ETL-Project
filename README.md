# ETL-Project
The purpose of this project is to gather information to better examine Education data.  
We will be corralating College enrollment data, household income, SAT scores, and average GPA.
The transformation of this data will better show statistics for base college enrollment.

The original data sources that were used for the extraction was the following:
    http://www3.cde.ca.gov/researchfiles/satactap/sat17.xls
    This data from the California Department of Education looking at SAT information by county, school, etc, in 2017.
    
    https://factfinder.census.gov/faces/tableservices/jsf/pages/productview.xhtml?pid=ACS_17_5YR_S1901&prodType=table
    This was the tool used to find Census data from the state of California looking at household income for the year of 2017.
    
    Both data sets were formatted as CSV files.
    
 Transformation
    As there was a lot of unnecceary data in both sets we decided to focus looking at select information from both sets.
    Using Jupyter notebook we narrowed down the scoped of information to the point that we were satisfied with what data we
    would used for a new database.
    
    Then by using MySQL we then joined the two data sets using the county as the common column.
    
    The reason why these data sets were chosen was to potentially show that areas that are more afluent have better SAT scores
    They would have more access to resources for students in which they can succeed.
