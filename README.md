## MTA-Subway and Newyork Restaurants Data-Analysis
The purpose of my EDA study is to propose to open a Turkish doner restaurant in Newyork region, 
using Newyork MTA Metro data and Newyork Restaurant data.

**The New York subway MTA turnstile** data is a series of data files containing cumulative number of entries and exits by station, 
turnstile, date and time. Data files are produced weekly, data records are collected typically every 4 hours with some exceptions.

In this analysis we use data from on May 2020. 

Variables included in initially processed data:

* C/A = Control Area (e.g., A002)
* unit = Remote Unit for a station (e.g., R051)
* SCP = Subunit Channel Position represents an specific address for a device (e.g., 02-00-00)
* station_code = C/A + unit, locating a station
* turnstile = C/A + unit + SCP, locating a turnstile
* Station = Represents the station name the device is located at
* date = Represents the date (MM-DD-YY)
* time = Represents the time (hh:mm:ss) for a scheduled audit event
* datetime = date + time (MM-DD-YY hh:mm:ss)
* desc = Represent the "REGULAR" scheduled audit event (Normally occurs every 4 hours)
* entries = The comulative entry register value for a device
* exits = The cumulative exit register value for a device

I got Newyork Restaurant information from the website 
https://data.ny.gov/Health/DOHMH-New-York-City-Restaurant-Inspection-Results/43nn-pn8j.
File name is **DOHMH_New_York_City_Restaurant_Inspection_Results** 
This dataset and the information on the Health Department’s Restaurant Grading website come from the same data source. 
The Health Department’s Restaurant Grading website is here:
http://www1.nyc.gov/site/doh/services/restaurant-grades.page
See the data dictionary file in the Attachments section of the OpenData website for a summary of data fields and allowable values.

[Newyork Restaurant view data](https://data.ny.gov/Health/DOHMH-New-York-City-Restaurant-Inspection-Results/43nn-pn8j/data)
