# Citi Bike Analysis
## Project overview
NYC bike sharing service Citi Bike was part of a positive experience for two entrepreneurs while on vacation, and they want to analyze data from Citibike to see if it would be viable to create a similar business based in Des Moines, IA.

## Resources
* Software:  Python 3.9.7, Anaconda 4.12.0, Jupyter Notebook 6.4.5, Tableau Public 2022.1.2
* Data:  https://s3.amazonaws.com/tripdata/index.html

## Results
Data was tabulated by the number of trips by both subscribers and casual customers and by gender (male, female, and unknown/undisclosed), and it was found that mostcustomers are male subscribers, followed then by female subscribers.  Most of our unknown/undisclosed users are not subscribers, suggesting they may be casual users who didn't care to completely fill out their sign-up surveys.

Trip durations tend to be approximately 20 minutes or less, which appears to be true regardless of gender, suggesting that bike stations should be fairly close together.

The most bikes were checked out between the hours of 7am and 9pm.  There is relatively little utilization before 7am and after 10pm in general.  Regardless of gender, subscribers used the bike share most actively on week days, suggesting again that the service is being used for daily commutes.  Non-subscriber customers used the service most heavily on weekends, suggesting their primary purpose may be for leisurly activities.


# Summary
New York City is very different from Des Moines, IA.  People live close enough to their jobs that they can ride a bicycle, where the population is far more spread out in Des Moines and people have much longer commutes.  This means that a bicycle sharing business would have to focus on tourists and explorers, where Citi Bike's largest user base appears to be week-day commuters.  Next steps might include more closely exploring Citi Bike trips that occurred on weekends since these users would be more like the type of user expected in Des Moines, to determine their trip durations, and then plotting landmarks and points of interest around Des Moines to see how likely it would be that tourists might bike those distances or if their just too far apart.

To see the full analysis in Tableau, please go to:
https://public.tableau.com/app/profile/marsha.curtis/viz/CitibikeChallenge_16561719519930/CitibikeStory?publish=yes
