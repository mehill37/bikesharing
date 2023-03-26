# bikesharing

## Summary
Using Tableau to create visualizations of the NYC citibike data. Displaying bike trip analysis to convince investors that a bike-sharing program in Des Moines is a solid business proposal.
Question's we need to answer with our new data:
- Where are the most popular starting/ending locations?
- What time of day are bikes used the most/least?
- Who uses the bikes the most and how long are the bikes being used for by whom?

## Overview
The Tableau Dashboard, used to create a story/summary of the data found, is any easy way to create a presentation for the propsal.

<p align="center">
Displayed is the Dashboard that would be presented to investors.
<img src="https://github.com/mehill37/bikesharing/blob/b113e1780a1670a743d7f465d39abb565a1d7c76/images/Dashboard_Citibike.png">
</p><br/>

## Results

- The data pulled for August 2019 citibike had to be adjusted to reflect trip durations by date-time. Below is the newly adjusted data.

<p align="center">
<img src="https://github.com/mehill37/bikesharing/blob/b113e1780a1670a743d7f465d39abb565a1d7c76/images/tripduration_datetime.png">
</p><br/>

- This line graph shows the total bikes that are activated. From the image, the peak # of bikes are activated 10 mins into the ride. After about an hour, there are very few bikes that are active. 

<p align="center">
<img src="https://github.com/mehill37/bikesharing/blob/b113e1780a1670a743d7f465d39abb565a1d7c76/images/checkout_users.png">
</p><br/>

- This visualization is similar to the previous one displayed except gender is added as a variable. What is determined from adding gender is males are the most active users. They are more than double female users.

<p align="center">
<img src="https://github.com/mehill37/bikesharing/blob/b113e1780a1670a743d7f465d39abb565a1d7c76/images/checkout_gender.png">
</p><br/>

- The following image is a heat map where the darker the squares the higher the bike activity. Monday through Friday, the most popular times are 7-9am and 5-6pm. This could be an indication that people are using bikesharing as a form of commuting and/or working out before or after work. Other popular times are Saturday and Sunday afternoons which could indicate that people are wanting to use bikesharing in their free-time given that most people have that time free.

<p align="center">
<img src="https://github.com/mehill37/bikesharing/blob/b113e1780a1670a743d7f465d39abb565a1d7c76/images/trips_weekday.png">
</p><br/>

- Comparable to the previous heat map, but this heat map adds the gender variable. Still confirming our previous conclusion of males using them more often and the times of day stay the same.

<p align="center">
<img src="https://github.com/mehill37/bikesharing/blob/b113e1780a1670a743d7f465d39abb565a1d7c76/images/trips_week_gender.png">
</p><br/>

- This chart categorizes bikesharing users by gender and also by usertype (subscriber vs. customer). This is another heat map that clearly displays subscribers are more active than customers. Thursday's and Friday's are the most popular days of the week with more male subscribers than female overall.

<p align="center">
<img src="https://github.com/mehill37/bikesharing/blob/b113e1780a1670a743d7f465d39abb565a1d7c76/images/usertrips_gender_week.png">
</p><br/>

