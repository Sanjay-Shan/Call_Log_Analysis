# Call_Log_Analysis

This Project is a part of my personal projects. The main motive of this project is to perform a thorough analysis on my personal call logs.In the below section, I'll be talking more about the tasks that will be performed in the analysis.Before that I would like to walk through the process of Data Collection, which stands a important part after the data cleaning.

## Data Collection
Mostly 2 Kinds of data were collected for this project,namely

1. Call Logs :  This required me to utilize Tmobile app, which gave me the access to nearly 1 year of call logs. So, a total of 12-13 monthly call logs in the .csv format were collected. Other options that were explored include touchcopy and iBackup extractor. But were set aside due to limitations they probed in terms of the access to the limited data.

2. Contacts : The sole purpose of accessing the contacts was to identify the person in the data analysis. Since the contacts were not directly accessible through the Iphone, Google Contacts was chosen as the medium for the data. Furthermore, Google contacts lets you download/import the data in 3 different formats ,namely
    1. google(CSV)
    2. Outlook(CSV)
    3. .VCF -- Virtual Card Format -- a means of storing contacts in the digital format.

## Data Cleaning
A thorough cleaning had to be performed because of the complexity in the format of the data. Few of the steps taken in cleaning the data
    1. Merging of the year long csv file ensuring proper indexing and appropriate column naming convention
    2. Conversion of the mixed 12/24 hr format to 24 hr format
    3. Getting the duration in the 'int64' format from the string format
    4. Correcting the format of the Call Destination
    5. Removing the duplicates in the Contacts
    6. Performing Feature engineering to create a new column the full name of the contact
    7. Handling of the multiple contacts of the user
    
## Data Analysis and Visualization
The project is still in the process of deep data cleaning, but things have already been plannned in prior towards the motive of this project
    1. Thorough analysis of call patterns of a individual contacts
    2. Most frequent caller on regular basis (day, week, month etc)
    3. Analysis of missed calls, average response time, Incoming calls, outgoing calls
    4. Identification of missed calls -- Using the contact name
    5. Identification of near and dear ones (determined by the frequency of the calls)
    6. Normal + WhatsApp merged call history analysis
    7. Average time spent on phone call on a daily statistics

## Future Perspective
This project aims to provide a real time statistical analysis of the call history for any person by integrating it with the tools like PowerBI. Stay tuned as more analysis would be added to further enhance the output of this project.
