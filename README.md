# Weekdays Are for the Boys: Understanding the Outsized Role of Gender in Bikeshare Usage

## Purpose
The purpose of this report is to analyze data from New York City's CitiBike program, using both Tableau and Python, to debrief a fictional investor
in hopes of replicating the idea in Des Moines, Ia. This analysis specifically shows how males commuting to and from work appear to favor the program over
females and non-identifiers, posits some reasons why, and suggests ways in which a future program could be more inclusive.

## Analysis
Again, the data covered in this report come from New York City in August, 2018. It's possible that slice isn't completely representative of the rest of the year.
However, it's clear in this sample that male riders are much more common than female riders or non-identifiers.

<img width="252" alt="Gender_breakdown_male" src="https://user-images.githubusercontent.com/1015285/126915370-40fe3d5a-baba-4779-b089-41b66eec76e5.png">

<img width="257" alt="Gender_breakdown_female" src="https://user-images.githubusercontent.com/1015285/126915414-9b0a154e-e4eb-4915-b2e3-9d307ecd4c21.png">

The most popular times to check out a bike also coincide with popular commute times in the mornings and evenings.

![image](https://user-images.githubusercontent.com/1015285/126915468-b90b985f-ae26-4670-9847-13c5cb234f63.png)

Most trips are only a handful of minutes. In August, more than 146,700 trips took roughly 5 minutes.

![image](https://user-images.githubusercontent.com/1015285/126915498-946e73e0-3f73-4866-9c83-fc8fc063738b.png)

And that goes for both males and females, though females' most common duration was more like 7 minutes, and non-identifying individuals' trips were spread out a bit more.

![image](https://user-images.githubusercontent.com/1015285/126916205-a6745859-10e5-4fd9-b507-dd55ab21dc88.png)


The heatmap below also helps illustrate the bias toward workday commute biking. There appears to be an interesting drop-off on Wednesdays, but for the most part, Mondays through Fridays, between 7 and 9 a.m. and 5 and 7 p.m., appear to be the most popular times to use CitiBike. Note there is much more midday use on Saturdays and Sundays. The usage is lighter for females, but mostly follows the same pattern.

![image](https://user-images.githubusercontent.com/1015285/126915706-9e00e006-071f-41bf-a66a-8bdf76270df5.png)

![image](https://user-images.githubusercontent.com/1015285/126915722-1fbed03d-a4d4-473c-9d32-6ec29c650eaf.png)

Finally, it's important to note that casual users (customers) don't appear to display the same preference for workday commuting with CitiBike that subscribers do. The casual users, whether male, female or non-identifying, seem to use the program more frequently on the weekends. Still, the pattern identified throughout the rest of the analysis appears to be consistent for subscribers.

![image](https://user-images.githubusercontent.com/1015285/126915799-8e360390-ac62-4ef5-b3e6-58af166cd301.png)

## Summary
Male users taking short trips to and from work appear to get the most out of New York City's bikeshare program -- at least during the time period analyzed here, August of 2018. It would be helpful to extend this analysis to different months of the year. A heatmap of checkout times by weekday during a different season -- say, October or February, might suggest ways to keep the program viable during months in which usage dies down. Additionally, a deeper analysis of female and non-identiying users could help a theoretical bikeshare company figure out ways to bring them into the fold as customers more frequently. It would be interesting to see if they tend to check out bikes around particular parts of the city by creating a histogram of their most commonly-used start and end stations, or if their usage in particular fluctuates over the course of the year with a line graph of data for the entirety of the year showing number of rides per month.
