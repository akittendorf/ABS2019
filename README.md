# ABS2019

## WHAT: 
This project sources data from the United States Census Bureau's 2019 Annual Business Survey APIs (https://www.census.gov/data/developers/data-sets/abs.2019.html) to examine economic and demographic factors of businesses and business owners in the United States, Wisconsin, and Minnesota.  

Project techniques include: 
* API calls   
* pandas   
* matplotlib.pyplot  
* seaborn

## REQUIREMENTS:
Code files were written using Jupyter notebooks with Python version 3.9.7. Functionality may vary with differing versions.

## MODULES USED: 
* pandas  
* matplotlib.pyplot  
* seaborn  

## MAINTENANCE:
This was created for an assignment and will likely not be updated after 1/16/2022.

## REPOSITORY CONTENTS:
* README.md  
* ETLandCode (folder): ______.ipynb, ______.ipynb, _______.ipynb, _______.ipynb  
* projectreport
    
All .ipynb files in ETLandCode contain code and the ETL to obtain and visualize data from the 2019 ABS APIs. Each file utilizes the Company Summary API and examines the number of employer businesses in the United States, Wisconsin, and Minnesota by a different factor. 
* ____.ipynb: industry sector   
* ____.ipynb: customer type   
* ____.ipynb: business owner sex    
* ____.ipynb: business owner race group    
              highest level of education obtained prior to becoming an owner - utilizes the Characteristics of Business Owners API

projectreport  
This file includes a detailed report of the project findings.

## USAGE:
The intention of this project was not to create an application. However, if someone wanted to run our code, they could clone the repository. The files in this repository do no need to be placed within the same directory, although that is recommended to maintain file organization.  

**Note** The 2019 ABS APIs require and API key. For confidentiality, our personal API key has been removed from the files and is only referenced in a variable. You may obtain an API key at this link: https://www.census.gov/data/developers/guidance/api-user-guide.Help_&_Contact_Us.html and substitute your API key where indicated in the .ipynb API calls.

## AUTHORS: 
buxto, GrudtB, rrh345, akittendorf