# Team_3_Project

## Team Members
* Paige Curl
* Kaila Person
* Tony Lew
* Takemi Oshiro

## Project Overview
- Our selected topic is to analyze Citi Bike System data to determine popularity of bikes. 
- The data source is CitiBike trip data that inclues trip ride history such as ride id, latitude/longitude, member status, ride type, station information, and time details. 
- We hope the data answers the queston if classic or electric bikes are more popular among members, non-members, and casual riders.
- The data exploration phase of the project is determing if a machine learning model will answer our question. 
- The data analysis phase of this project is testing different parts of our data to see if we can see any trends.
- The languages used to do this project is jupyter notebook.
- The result of the analysis showed that classic bikes were more popular among users than eletrical bikes.
- Recommendation for future analyis would be to show the total trip duration for each ride type to show more accuracy amongst the data.
- Together as team we can agree we would of chose a better data set that can better be used with machine learning. 

- Google slides draft presentation: https://docs.google.com/presentation/d/1FqecNmbd_gwxxS7AX8PIOkSJ6fMpdwfDbjfoaA93WbU/edit?usp=sharing 

## Reason for selected topic

The reason we selected the topic is due to our familiarity with the topic and having a good source of data to explore questions within the topic.

## Communication Protocols 
The communication protocols for the group will be to meet after class times, one additional time outside of class, and keep up daily communication as needed via Slack.

## Data Source 

The chosen data file is too large to be uploaded into github. Team members are able to access data source by doing the following :
1. Clicking the following link: https://s3.amazonaws.com/tripdata/index.html .
2. Finding the data source named " 202111-citibike-tripdata.csv.zip", date modified "Apr 7th 2022, 12:18:06 pm" 
3. Downloading the data source onto their computer/laptop.

We sourced our data from the citibike website where they offer data repositories to the public.

Selecting our data source we took into account the size of the content in reference to what we hoped to achieve at this projects completion. We decided that the trip data for citibike fit our needs the best. 
In the process of cleaning the data we where able to utilize and/or try multiple option in removing columns adding columns and calculating new values. One of our challenges was utilizing new techniques that we found in our google searches outside of the class modules. For example the Haversine function in python used to calculate the distance between two points on a curved surface.

## Database
AWS

### Confusion Matrix Summary:
* "Pre" (Precision - the ratio of CORRECTLY predicted "positives" to the TOTAL number of "positives")
* "Rec" (Recall aka True Positive Rate)
* "Spe" (Specificity aka True Negative Rate)
* "F1-Score" (Harmonic Mean of PRECISION & RECALL)
* "Geo" (Geometric Mean - the square root of the product of RECALL & SPECIFICITY)
* "IBA" (Index Balanced Accuracy)

![LogReg1](https://user-images.githubusercontent.com/99851509/184422908-678fdbcc-7c3c-4ad3-85f5-46814167f940.png)
![LogReg2](https://user-images.githubusercontent.com/99851509/184422965-32514464-56b4-4917-8f68-9f2c0063e01e.png)

### Decision Tree Matrix 
![DecTree1](https://user-images.githubusercontent.com/99851509/184423079-a97b5a2f-0ea0-4bcc-9149-ef5ba89074e2.png)

Part of the difficulty of Machine Learning models are questions we all ask when using them: which one should I use and why?  Trying to decide what we want the dataset to tell us and then deciding a classification model is enough to make your head spin.  In the dataset that we chose which was very large, we tried several different models of which some did not work because of the size of the dataset.  One in particular was the Random Forest model.  With over 2 million rows, it was not able to process this much information.  Fortunately (see above) the Logistic Regression and Decision Tree models were able to process this large dataset.
The primary difficulty we encountered was cleaning (pre-processing) this dataset as well.  This required the whole group's efforts and initiative to make this work.  The dataset being used was not the original dataset we chose.  That dataset also had elements in its features that were not compatible with machine learning model formats.  Changing datasets when we were about a week & a half into the project was decision faced with apprehension from everyong in the group.  We hope the above results show some of the range of knowledge gained from the workload from this course.

### Results & Summary
[Let's Go Ride A Bike](https://public.tableau.com/shared/QWTX7HCJH?:display_count=n&:origin=viz_share_link)

When to use and What to ride! A visual representation.

There are clearly defined peak hours that correpond to useage despite subscription type. This allows for simplicity in scheduling maintenance staff, asset balancing staff and controlling costs due to payroll. 
Members clearly prefer electric drive bikes to manual drive ones. The relative mix of drive types available should be adjusted for each area depending on the ratio of subscription members to casual users.
![image](https://user-images.githubusercontent.com/101307058/184520575-252f3666-839b-454d-9d78-975194c81649.png)

Electric bikes are used to travel almost twice as many miles as manual ones. Using this fact along with the usage schedule, member type data and varying electric rates by time; we can plan out chargin times for the many batteries employed to minimize utility costs while maximizing convenience for our customers.

![image](https://user-images.githubusercontent.com/101307058/184520582-56915bcf-1687-4aef-99e8-465e57fafa78.png)

There is a clear preference for electric drive bikes by subscription members. There is also a marked diffeence in the distance traveled by those same members.

![image](https://user-images.githubusercontent.com/101307058/184785006-7a934d18-96cf-48f1-8166-a0f052b84a66.png)

Some things that should be taken into account in regards to budgeting for new expansions should take into account the member type.

![image](https://user-images.githubusercontent.com/101307058/184785032-bdb043ef-5ec5-4f70-a8dd-763fcd470aa2.png)

In adition, analysis of multiple data sets should be preformed and the results should be compared against each other to identify larger trends and/or paterns and to help weed out any short term anomolies that might skew the reults. comparing multiple geopgraphical areas should be helpful to identify trends or see if the same results hold true wherever the program is rolled out.
