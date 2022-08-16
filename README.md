
# Team_3_Project


## Bikesharing Miles Traveled By Type

In this group project we utilized many tools to allow us to reform our data. Allowing us to build a presentation that would break down the difference in the distance people traveled by the type of bike they chose.

## Tools 
* Jupyter Notebook
* Python
* Tableau
* Haversine
* sklearn
* hvplot


* Read in data
* clean data
* create 2 new csv files 
* join the 2 csv files
* separate rideable_type
* sort by rideable_type
* create a machine learning type
* create visualizations in tableau


## Team Members
* Paige Curl
* Kaila Person
* Tony Lew
* Takemi Oshiro

## Project Overview
- Our selected topic is to analyze Citi Bike System data to determine popularity of bikes. 
- The reason for the selected topic is to use machine learning to easily detect trends. 
- The data source is CitiBike trip data that inclues trip ride history such as ride id, latitude/longitude, member status, ride type, station information, and time details. 
- We hope the data answers the queston if classic or electric bikes are more popular among members, non-members, and casual riders.
- The data exploration phase of the project is determing if a machine learning model will answer our question. 
- The data analysis phase of this project is testing different parts of our data to see if we can see any trends.

## Communication Protocols 
The communication protocols for the group will be to meet after class times, one additional time outside of class, and keep up daily communication as needed via Slack.

## Data Source 
The chosen data file is too large to be uploaded into github. Team members are able to access data source by doing the following :
1. Clicking the following link: https://s3.amazonaws.com/tripdata/index.html .
2. Finding the data source named " 202111-citibike-tripdata.csv.zip", date modified "Apr 7th 2022, 12:18:06 pm" 
3. Downloading the data source onto their computer/laptop.

## Database
Possible database to consider 'SQLite'(no application needed) or 'R'

### Confusion Matrix Summary:
* "Pre" (Precision - the ratio of CORRECTLY predicted "positives" to the TOTAL number of "positives")
* "Rec" (Recall aka True Positive Rate)
* "Spe" (Specificity aka True Negative Rate)
* "F1-Score" (Harmonic Mean of PRECISION & RECALL)
* "Geo" (Geometric Mean - the square root of the product of RECALL & SPECIFICITY)
* "IBA" (Index Balanced Accuracy)

### Results & Summary
[Let's Go Ride A Bike](https://public.tableau.com/shared/QWTX7HCJH?:display_count=n&:origin=viz_share_link)

When to use and What to ride! A visual representation.

There are clearly defined peak hours that correpond to useage despite subscription type. This allows for simplicity in scheduling maintenance staff, asset balancing staff and controlling costs due to payroll. 
Members clearly prefer electric drive bikes to manual drive ones. The relative mix of drive types available should be adjusted for each area depending on the ratio of subscription members to casual users.
![image](https://user-images.githubusercontent.com/101307058/184520575-252f3666-839b-454d-9d78-975194c81649.png)

Electric bikes are used to travel almost twice as many miles as manual ones. Using this fact along with the usage schedule, member type data and varying electric rates by time; we can plan out chargin times for the many batteries employed to minimize utility costs while maximizing convenience for our customers.

![image](https://user-images.githubusercontent.com/101307058/184520582-56915bcf-1687-4aef-99e8-465e57fafa78.png)

![image](https://user-images.githubusercontent.com/101307058/184785006-7a934d18-96cf-48f1-8166-a0f052b84a66.png)

![image](https://user-images.githubusercontent.com/101307058/184785032-bdb043ef-5ec5-4f70-a8dd-763fcd470aa2.png)



