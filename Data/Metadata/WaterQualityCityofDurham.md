# Water Quality Dataset


## Summary
This dataset was prepared for the City of Durham

The dataset contains data from water quality monitoring of 30 parameters in Durham since 2004.

## Database Information

Data were collected creating a username and password and then seelcting the data for Ellerbe Creek and using the Download tool (http://www.durhamwaterquality.org/).

csv files were saved as `ParamDurhamData_raw.csv`.

Data was downloaded 07-2022.

## Data Content Information

Column names without descriptors are self-explanatory.

"id"  
"Station.Name"  
"Filtered"    
"Parameter"             
"Date.Time"             
"Value"                
"QA.Code"               
"Unit"                  
"QAQC.Sample"          
"Comments"              
"Rain.in.Last.24.Hours" 
"Sky.Condition"        
"Flow.Severity"         
"Comp..Code"            
"Thalweg"              
"Lab"                   
"Project"

id: order number
Station Name: Collection site
Filtered: the place where the sample was filtered
Parameter: water quality parameter         
Date Time: month/day/year  hh:mm:ss AM/PM          
Value: parameter value                
QA Code: Quality assurance code           
Unit: parameter unit              
QAQC Sample: Duplicate or Blank        
Comments: relevant information about the sample             
Rain in Last 24 Hours: Yes/No
Sky Condition: relevant for field monitoring       
Flow Severity       
Comp Code: Internal code            
Thalweg : Yes/No             
Lab : Lab in charge                 
Project: Ambient

## Naming conventions and file formats
Files are named according to the following naming convention: `datatype_details.format`, where: 


**datatype** is a description of data 

**details** are additional descriptive details, particularly important for processed data (wrangle, etc)

**format** is a non-proprietary file format (e.g., .csv, .txt)

## Additional Information and Support
For more information, please contact the data assembler, **Joanna Huertas** (jkh64@duke.edu)