# Airline-data-project
This is a simple project to demonstrate the basic processes of data engineering using some sample website airline data found here https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/HG7NV7. 
it seeks to harness the power of data analytics to answer some pertinent questions about the dataset which are as follows:

    When is the best time of day/day of week/time of year to fly to minimise delays?
    Do older planes suffer more delays?
    How does the number of people flying between different locations change over time?
    How well does weather predict plane delays?
    Can you detect cascading failures as delays in one airport create delays in others? Are there critical links in the system?
    
These questions would be clearly answered on visual dashboard reports for easy consumption.


**This data would be extracted from the source using cloud based tools and technologies for all the involved processes. The warehouse tables will be partitioned and clustered in a way that makes sense for the upstream queries and the tranformations are defined with dbt.
