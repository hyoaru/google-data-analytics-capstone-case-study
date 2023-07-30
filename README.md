# Google data analytics capstone case study: How does a bike-share navigate speedy success?
As a junior data analyst working in the marketing analyst team of Cyclistic, a bike-share company in Chicago, the director of marketing believes that the company's future success depends on maximizing the number of annual memberships and with that being the case, our team was tasked to understand how casual riders and annual members use Cyclistic bikes differently. 

From these insights, our team will design a new marketing strategy to convert casual riders into annual members. 

However, the executives must first approve of our recommendations. In which, must be backed up with compelling data insights and professional data visualizations.

* Case study: [capstone-case-study.html](https://htmlpreview.github.io/?https://github.com/hyoaru/google-data-analytics-capstone-case-study/blob/master/capstone-case-study.html)
* Case study data preparation in python: [capstone-case-study-data-preparation.html](https://htmlpreview.github.io/?https://github.com/hyoaru/google-data-analytics-capstone-case-study/blob/master/capstone-case-study-data-preparation.html)

## Data source and organization
The data used for the case study on Cyclistic is sourced from https://divvy-tripdata.s3.amazonaws.com/index.html. Made available by Motivate International Inc. under  this [license](https://ride.divvybikes.com/data-license-agreement) The dataset contains historical data on bike rides. In which, contains the columns:
* **ride_id:** A unique identifier for each bike ride.
* **rideable_type:** The type of bike for which what the user used for the bike ride.
* **started_at:** The timestamp indicating the start time of the ride.
* **ended_at:** The timestamp indicating the end time of the ride.
* **start_station_name:** The name or location description of the docking station where the ride started.
* **start_station_id:** The unique identifier of the docking station where the ride started.
* **end_station_name:** The name or location description of the docking station where the ride ended.
* **end_station_id:** The unique identifier of the docking station where the ride ended.
* **start_lat:** The latitude coordinate of the docking station where the ride started.
* **start_lng:** The longitude coordinate of the docking station where the ride started.
* **end_lat:** The latitude coordinate of the docking station where the ride ended.
* **end_lng:** The longitude coordinate of the docking station where the ride ended.
* **member_casual:** The type of user, indicating whether the customer is a casual pass user or an annual member.

## Technologies used
* R and python
* r-tidyverse
* r-scales
* r-viridis
* python-pandas