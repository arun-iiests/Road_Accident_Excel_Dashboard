# Road_Accident_Excel_Dashboard
## Project Overview
This project aims to analyze a road accident dataset, focusing on key performance indicators (KPIs) such as severity distribution presented in a donut chart, monthly casualties trends illustrated with a line chart, and casualties based on road type, surface conditions, areas, light conditions, and vehicle modes using visual representations like bar charts and maps. The insights derived from this analysis will inform targeted interventions and policy enhancements to improve overall road safety. 

This Being my 1st Excel project has taught me a lot and it was an exciting journey to work on real dataset & enjoyed too during the process. The varoius process with my key learnings are listed below:

## Data Cleaning 
Firstly I took an overview of all columns of the dataset by adding filter and looked whether there were any blank,duplicate,typing error values or not. In Accident_Severity column I found that there a 'Fetal' kind of severity, So I corrected it to 'Fatal' by method of find and replace under home section  

![image](https://github.com/arun-iiests/Road_Accident_Excel_Dashboard/assets/124171557/4129b718-c983-46f9-86f3-3770016d42fe)

## Data Processing
1. Month name Extraction from Date format-->=TEXT([YourCellReference], "MMM")  
2. Year Extraction from Date format-->=TEXT([YourCellReference], "YYYY")

## Data Analysis And Visualisation
1. KPIs for accident on basis of severity  caused with donet chart highliting their percentage
2. Monthly Casualities Trends by line Chart
3. Casualities By Road Trend
4. Casualities By Road Surface
5. Casualities by area
6. Casualities light condition
7.  Casualities caused by various modes of vehicles



## Tools
- Excel
- Pivot Table
- Donet Chart and Its formating
- Bar Chart
- Tree Map etc.

## My Learnings
  1. Month and Year Extraction From date format by "TEXT" Function
  2. Pivot Table
  3. FUN + F4 --> To fix a cell
  4. Use of "Calculated Field and Calculated Item are features within PivotTables"  
     Go to the "Analyze" tab on the Ribbon.
     
     ![image](https://github.com/arun-iiests/Road_Accident_Excel_Dashboard/assets/124171557/884cee6d-0ddb-46b0-bc7c-05d0b546d445)
     
     In the dialog box, give your Calculated Item a name, and enter a formula using existing items.  Click "Add" and then "OK."
5. Adding Icons
6. Making Static Formula into dynamic Formula
7. Unit Conversion  
    Right Click--> Click On Format Cell --> Click On custom and did as shown
   
    ![image](https://github.com/arun-iiests/Road_Accident_Excel_Dashboard/assets/124171557/8fdc837b-707b-478d-8195-e4ea12f447b2)
 8. Adding Time Line and setting its connection & customization
9. Addition Of slicer connection setting
10. Inserting Hyperlink
11. So overall I learned an Excel Dashboard creation technique

### Data Source (Kaggle) 
No of Rows: 307974 

No of Columns: 21 

The Columns are: 

['Accident_Index', 'Accident Date', 'Day_of_Week',
       'Junction_Control', 'Junction_Detail', 'Accident_Severity', 'Latitude',
       'Light_Conditions', 'Local_Authority_(District)', 'Carriageway_Hazards',
       'Longitude', 'Number_of_Casualties', 'Number_of_Vehicles',
       'Police_Force', 'Road_Surface_Conditions', 'Road_Type', 'Speed_limit',
       'Time', 'Urban_or_Rural_Area', 'Weather_Conditions', 'Vehicle_Type']
    
 -[Dataset Link](https://www.kaggle.com/datasets/nezukokamaado/road-accident-casualties-dataset/data )     


