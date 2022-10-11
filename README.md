# Solitaire
## Dataset

The dataset, 201902-fordgobike-tripdata.csv, is downloaded from Ford GoBike and licensed by Ford GoBike. 
This dataset includes 183 412 bike trips with 16 features such as locations, time, and user attributes. 
There are start and end stations. I noticed that most trips happen at the same stations, 
so I subset the dataset by choosing top 10 trip start stations with the most trips.  
Thus, the following analysis is performed by this subsetted dataset.


## Summary of Findings

Univariate exploration: 
The number of trips gradually decreases when the weather becomes colder. 
During the day, there are more trips in the morning and afternoon than the night. 
Also, there are more trips during the weekdays and less trips during the weekends. 
It makes sense that there are more subscribers than customers. For the gender groups, 
the number of trips in male riders is 3 times more than the number of trips in females. 
It needs to be investigated more. 
Most of riders are between the ages of 30 to 40 years old and the duration of trips is around 650 seconds.

Bivariate exploration: 
There is a slightly negative correlation between age and duration of trips. 
After separating the top 10 stations, half of stations have the most trips in the morning 
and another half of stations has the most trips in the afternoon. 
Weekdays have the most trips than weekends. 
Biking is definitely correlated with the weather. 
It needs more weather forecast data to support the assumption.

Multivariate exploration: 
Separating user types, customers and subscribers, gives more insights. 
Customers like to bike during the weekdays. 
Also, the number of trips increases in the tourist attractions like Ferry building and Embarcadero. 
On the other hand, the trips in subscribers increase during the weekdays and after launching, 
the number of trips gradually increases and then decreases when the weather becomes colder. 
Moreover, customers ride longer than subscribers. 


## Key Insights for Presentation

The stations with the most trips are located in San Francisco and connect to public transportations 
including Caltrain, Bart and Ferry. User types play a key factor on the number of trips in each location and time group. 
For customers, there are more trips during the weekdays. They also have longer trips. 
On the other hand, for subscribers, there are more trips during the weekdays 
and the number of trips is influenced by the climate change. 
Thus, collecting more information individually from these two user types is important for the future analysis.
