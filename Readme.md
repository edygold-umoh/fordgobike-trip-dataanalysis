## Introduction

The dataset contains information on 183,412 bike trips provided by a bike-sharing program that operates in the greater San Francisco Bay region. Along with trip duration in seconds, the dataset also includes other features such as date and time, customer type, gender, and a few other variables.

---

### DATAFRAME WRANGLING AND ANALYSIS

The given dataset provides longitude and latitude coordinates for the start and stop stations of each trip, which enables us to calculate the distance between them using the Haversine function. By knowing the duration and distance of each trip, we can calculate the speed using the formula speed = distance / time.

The dataset consists of 183,412 rows and 25 columns, providing information on bike-sharing trips taken in the San Francisco Bay area. It includes variables such as duration (in seconds), date-time, customer type, gender, and others.

Based on your feature of interest, the main feature in the dataset would be the duration of the rides. You are interested in finding out if other features such as distance, member gender or age have an impact on the duration of the rides. Additionally, features such as distance and member age from birth year will support your investigation.

---

### SUMMARY OF FINDINGS

In addition, I found that the distance traveled on a trip is positively correlated with the trip's duration, indicating that longer distances contribute to longer trip durations. Furthermore, age was discovered to have a slight impact on trip duration, with younger riders taking slightly longer trips on average. Finally, the dataset revealed that less than 10% of all trips were bike sharing.

Also I discovered that non-subscribers spend far longer on their excursions than regular customers do, and women typically ride for longer than men do. Bicycles can only be shared on excursions by subscribers, and these journeys make up roughly 10% of all rides.

---

### IMPORTANT TAKEAWAY FOR PRESENTATION

I focus on the duration and frequency of bike rides per day and user type by removing other variables from the analysis. I start by using Seaborn Countplot to visualize and analyze the frequency of trips by day of the week and user type. Then, I separately analyze each categorical variable by creating boxplots that show the distribution of ride duration across different days and user types. I also use point plots to examine the effect of two other categorical variables, days and user type, on the duration of bike rides. I ensure that each categorical variable is represented by a distinct color palette to make it easy to distinguish between them.
