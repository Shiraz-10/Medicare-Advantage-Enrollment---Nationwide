MA Contract Directory Package

MA_Contract_Directory_YYYY_MM.zip
The MA_Contract_Directory_YYYY_MM.zip file is a compressed file (using SecureZIP) 
consisting of the following files:

Read_Me_MA_Contract_Directory.txt - this file
MA_Contract_Directory_YYYY_MM.xls - data in Microsoft Excel format
MA_Contract_Directory_YYYY_MM.csv - data in comma separated value (csv) format

Please note that anywhere you see YYYY it denotes the 4 digit year and MM = the 2 digit
month the data covers.

The two data files contain the same base rows of data, but the Excel version includes
header, footer and some totals rows that are not possible in the text version. 


The CSV file contains the following columns (these column names are included as the first row 
of data):

  Legal Entity Name - [text] - The legal name of the organization
  Organization Marketing Name - [text] - The name of the organization markets to beneficiaries
  Contract Number - [text] - The contract identifier 
  Organization Type - [text] - The type of contract held by the organization with CMS 
  Plan Type - [text] - The type of plan offered to beneficiaries
  Contract Effective Date - [date/time] - the date the contract began with CMS (in mm/dd/yyyy h:mm format)
  Tax Status - [text] - the contracts tax status
  Parent Organization - [text] - the name of the parent organization for this contract
  CMS Region Responsible - [text] - the CMS region responsible for contract oversite
  Enrollment - [text] - the number of beneficiaries enrolled in the contract when the file was produced (* = 10 or less)
  Legal Entity Street - the street address for the contract
  Legal Entity Street2 - additional street address for the contract if necessary
  Legal Entity City - the contract address city 
  Legal Entity State Code - the contract address state
  Legal Entity Zip - the contract address zip code
  Directory Contact Title - [text] - the contact person's title
  Directory Contact Last Name - [text] - the contact person's last name
  Directory Contact First Name - [text] - the contact person's first name
  Directory Contact Middle Initial - [text] - the contact person's middle initial
  Directory Contact Phone - [text] - the contact person's phone number
  Directory Contact Phone Ext - [text] - the contact person's phone extension (if necessary)
  Directory Contact Fax - [text] - the contact person's fax number (if available)
  Directory Contact Email - [text] - the contact person's email
  Directory Contact Street Address - [text] - the contact address
  Directory Contact Street Address2 - [text] - the contact additional address information
  Directory Contact City - [text] - the contact city
  Directory Contact State - [text] - the contact state
  Directory Contact Zip - [text] - the contact zip code
  Directory Contact Last Update - [date/time] - the date the contact information was last updated (in mm/dd/yyyy h:mm format)


This file contains data for the following organization types (where there are active contracts): 

  Local CCP
  Regional CCP
  MSA 
  PFFS 
  RFB - PFFS
  Demonstrations 
  National PACE 
  1976 Cost 
  HCPP - 1933 Cost

Special Notes:

  (1) The privacy laws of HIPAA have been interpreted to prohibit publishing 
  enrollment data with values of 10 or less. Consequently, some enrollment data
  in this file have been set to blank because the enrollment was 10 or less. 

  (2) Pilot contracts are excluded from this file. The aggregate enrollment for these contracts
  is available in the Monthly Contract and Enrollment Summary Report.