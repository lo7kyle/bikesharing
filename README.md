# bikesharing
Analysis and Visualization with Tableau

In this challenge we were given the task to use Tableau to visualize and analyze Citi Bike data. We used Tableau to see the relation between gender and the use of the Citi bikes. 

## Purpose:
The purpose of this challenge was to familiarize ourselves with another visualization tool in Tableau. We are given the task to take the Citi bike data and perform a quick date transform using Jupyter notebook then using the data to visualize the usage of the Citi bikes and gender vs duration.   

## Resources
* Data Sources: 
Citi Bike Data:
https://s3.amazonaws.com/tripdata/index.html

* Software: 
Jupyter Notebook 6.3.0
Tableau Public 2021.2

### Results:
The results of this challenge were creating multiple visualizations of User Trips by Gender and to create a story to explain our findings. You can use the below link to find the storyboard and dashboard. 

[link to storyboard](https://public.tableau.com/app/profile/kyle.lo1888/viz/Citibike_challenge_16286468652530/Story1?publish=yes "Link to Storyboard")

The best way to explain our findings would ask a question. The question can be as simple as: Where do most rides start out in New York? Where do most rides end?
In my storyboard that was my question I started off with. From the map and bar chart, we see that the top 10 starting stations share similarities with that of the ending station. 

![Top 10 Starting/Ending Stations](https://github.com/lo7kyle/bikesharing/blob/main/resources/Top%2010%20Starting-Ending.PNG)

This analysis reveals that most of the users are trying to visit or go to the same place. This is probably due to a combine of either work or tourism. From this analysis we can then ask the question how long are these rides and which Gender uses the bikes more often? From the image below we can see that males dominate the use of the Citi bikes. This can be due to many factors that we can only infer on but have limited data to support. We also see that the unknown probably from non-subscribers have the least amount of usage which accounts for the tourists.    

![Rides per Gender](https://github.com/lo7kyle/bikesharing/blob/main/resources/Rides%20per%20gender.PNG) 

Using a heatmap, we can better visualize when the usage of the bikes is the hottest (most used). From the Image below we see that bike usage is most hot during rush hour before and after work. This shows that these bikes are used as a form of public transportation more heavily than as a way tourists use to get around. 

![Rides per Gender by Hours](https://github.com/lo7kyle/bikesharing/blob/main/resources/Rides%20per%20gender%20by%20hours.PNG) 

Now that we see this information, we can summarize the gender usage in a dashboard below. From the dashboard below we see that Females have the longest average time, however there are more males using Citi bike so Males have a higher total trip duration. This tells us that males probably bike faster than females and get to their destination a lot quicker than females. We also see that the average duration for the Unknown is highest amongst Males and Females meaning tourists tend to use the bikes for longer and leisure than subscribers who use it to for commute to work. 


![Gender Dashboard](https://github.com/lo7kyle/bikesharing/blob/main/resources/gender%20dash.PNG) 

### Summary:
In summary we can conclude that predominantly males use Citi bikes compared to females and unknowns. We can also conclude that the subscriber males use it for a means of quick commute whereas tourists and unknown use the bikes for longer and leisure. We also see that during rush hour and throughout the week males use the Citi bikes the most. In New York, many people use the subway station as a form of transportation and there is a possibility that females would rather use the subway than to bike. There are also many other factors that can play into this such as there are more males dominating the type of work in that area of New York so there are probably more males using the bikes. Like mentioned in my results, there are many factors that we can only infer on and not conclude. We can also infer that female feel unsafe using these bikes either because of the busy traffic of New York or of potential muggers. The next business question we can now ask is how to increase female usage of the Citi bikes. There can be implementation of security for females who find the bikes unsafe. Possibly add a bright light to the bike to increase visibility. We can also include a way to share your location to fellow coworkers or your boss so they know where you might be in case something happens to you. Citi might also be trying to take this bike idea and implement it to another city besides New York. One question that might need to be asked is population density and how many people come from outside the city to work compared to those who live in the city and work.
