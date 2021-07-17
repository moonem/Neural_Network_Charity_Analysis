# Neural_Network_Charity_Analysis

## Overview of the Analysis

The purpose of this analysis is to create a binary classifier that is capable of predicting whether applicants will be successful if funded by the charity organization *Alphabet Soup*. 

  ### Data Source and Features
  
The analysis will be based on a dataset as a *.csv* file containing more than **34,000 organizations** that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as the following:

  - **EIN** and **NAME**—Identification columns
  - **APPLICATION_TYPE**—Alphabet Soup application type
  - **AFFILIATION**—Affiliated sector of industry
  - **CLASSIFICATION**—Government organization classification
  - **USE_CASE**—Use case for funding
  - **ORGANIZATION**—Organization type
  - **STATUS**—Active status
  - **INCOME_AMT**—Income classification
  - **SPECIAL_CONSIDERATIONS**—Special consideration for application
  - **ASK_AMT**—Funding amount requested
  - **IS_SUCCESSFUL**—Was the money used effectively
 
 ## Results
 
  ### Data Preprocessing
  
  As mentioned earlier there are a total of **12 columns** in the *charity_data.csv* file. Fig. 1 shows the imported dependencies and part of the **application_df** dataframe with data from *charity_data.csv*. 
  
  
  ![application_df](Resources/dependencies_application_df.jpg)
  
  The **EIN** and **NAME** columns seems to have no impact on the decision making of whether an applicant for funding will be successful or not. 
