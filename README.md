# Does planned maintenance reduce ad hoc maintenance work?

## Motivation for this study
There are 2 types of Maintenance in general.
1) Planned Maintenance (Overhaul) which are conducted on an interval, to replace aging component and to capture hidden defect, before it becomes a service defects.
2) Ad-Hoc Maintenance which are unplanned work; to rectify a service defects.

Ideally, time-based maintenance is suppose to reduce ad-hoc maintenance, when done properly. Hence, we can do a study to check if there is a reduction in defects when a time-based maintenance is completed. 

## Data 
Data used for this case study are gathered from a train operator based in a highly populated and warm area. Reported Aircon faults are dated between 2016-Jan to 2022-Mar. There are 8 trains with aircon Overhauled within this period, which is in another dataframe. Sensitive information has been replaced with a dummy information.

There are 3 columns for aircon defects sheet

 1. Record - Date of the reported aircon fault    
 2. Cause - Types of Aircon Fault.       
 3. Train Number - Train Number for the reported defective Aircon

There are 2 columns for aircon defects sheet

 1. Overhaul Date - Date of the Aircon Overhauled
 2. Train Number - Overhauled Aircon Train Number.

## Step

Steps involved in this study include

1. Cleaning of data - removal of unncessary data and joining 2 dataframe - Using Pandas library.
2. Explortary Data Analysis - explore interesting trend in the data - Using matlibplot and seaborn library.
3. Feature Engineering - creating feature data to check if overhauled aircon trains causes adhoc defects reduction.

## Summary

The final score shows that all the airocn defects found in the overhauled trains has no reduction post-overhaul. This might due to various reasons but the most common one is current defects found in aircon system are not within the scope of the aircon overhaul. However, overhauling of aircon has it merit but we should not gauge its effectiveness based on Ad-Hoc Maintenance.

