# Team_3_Project

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

![LogReg1](https://user-images.githubusercontent.com/99851509/184422908-678fdbcc-7c3c-4ad3-85f5-46814167f940.png)
![LogReg2](https://user-images.githubusercontent.com/99851509/184422965-32514464-56b4-4917-8f68-9f2c0063e01e.png)

### Decision Tree Matrix 
![DecTree1](https://user-images.githubusercontent.com/99851509/184423079-a97b5a2f-0ea0-4bcc-9149-ef5ba89074e2.png)

Part of the difficulty of Machine Learning models are questions we all ask when using them: which one should I use and why?  Trying to decide what we want the dataset to tell us and then deciding a classification model is enough to make your head spin.  In the dataset that we chose which was very large, we tried several different models of which some did not work because of the size of the dataset.  One in particular was the Random Forest model.  With over 2 million rows, it was not able to process this much information.  fortunately (see above) the Logistic Regression and Decision Tree models were able to process this large dataset.
The primary difficulty we encountered was cleaning (pre-processing) this dataset as well.  This required the whole group's efforts and initiative to make this work.  The dataset being used was not the original dataset we chose.  That dataset also had elements in its features that were not compatible with machine learning model formats.  Changing datasets when we were about a week & a half into the project was decision faced with apprehension from everyong in the group.  We hope the above results show some of the range of knowledge gained from the workload from this course.

### Results & Summary
