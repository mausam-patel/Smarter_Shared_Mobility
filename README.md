# Tech + Research: Technica Hackthon 2019 Research Project
Citi Bike Analysis for investigating smarter shared mobility methods by applying predictive models

Tech + Research is a program where selected students can work with a professor to explore a research area through an applied project. 

This project involves quarterly trip data from Citi Bike (as described below). The scope of this project was to analyze the provided data and Vinit Shah's
previous work and analysis of the data, and to identify new opportunities for analysis and insight. We decided to move forward by using regressions, predictive 
models, and neural network concepts and tools (such as the MLPClassifier) to predict the most popular stations and bike shortages by time of day. Thus, we could 
recommend to the company that they can leverage the self-driving feature of the bikes and their apps to redistribute bikes based on which stations have 
shortages or where demand is the highest (most popular stations). We also accurately created a model to predict the most popular gender at a given station at a 
certain time with over 90% accuracy. We could recommend that the company could use this information to specialize ads at the stations based on these demographics. 

Work was conducted in Jupyter Notebook and tools just as Pandas and scikit-learn were used to complete this analysis. The original ReadMe, as well as the link 
to the page of the original project from which this one was inspired, can be found below. 




# Original CitibikeAnalysis From Vinit Shah [Can be Found Here] https://github.com/vinit28/CitibikeAnalysis
Citibike Analysis for Data Science Certification

Overview:

Your client, The Mayor of New York City, needs a better understanding of Citi Bike ridership. He wants an Operating Report for the Year of 2017 on his desk by the end of the week. Based on previous engagements we know the mayor is a big fan of visualizing data in charts.

Luckily, Citi Bike publishes quarterly trip data available for you to download and analyze. The data includes:

*	Trip Duration (seconds)
*	Start Time and Date
*	Stop Time and Date
*	Start Station Name
*	End Station Name
*	Station ID
*	Station Lat/Long
* Bike ID
*	User Type (Customer = 24-hour pass or 3-day pass user; Subscriber = Annual Member)
*	Gender (Zero=unknown; 1=male; 2=female)
*	Year of Birth

Specifically, the Mayor wants to see a variety of data visualizations to understand
1)	Top 5 stations with the most starts (showing # of starts)
2)	Trip duration by user type
3)	Most popular trips based on start station and stop station)
4)	Rider performance by Gender and Age based on avg trip distance (station to station), median speed (trip duration / distance traveled)
5)	What is the busiest bike in NYC in 2017? How many times was it used? How many minutes was it in use?
Additionally, the Mayor has an idea that he wants to pitch to Citi Bike and needs your help proving its feasibility.

He would like Citi Bike to add a new feature to their kiosks: “Enter a destination and we’ll tell you how long the trip will take”.
We need you to build a model that can predict how long a trip will take given a starting point and destination. 
