# Indian Airlines Ticket Price Analysis

## Objective

Seeking to delve into the dynamics of aviation amidst fluctuating market conditions, I, an avid aviation enthusiast, find myself drawn to the realm of flight each time I embark on a journey. The aftermath of the Covid-19 pandemic witnessed a gradual resurgence in the aviation sector from the depths of plummeting ticket prices experienced at the peak of the crisis. However, the current geopolitical tension stemming from the conflict in Ukraine coupled with the surge in aviation turbine fuel (ATF) prices has propelled ticket fares to unprecedented heights.
Motivated by this paradigm shift, I have embarked on an exploratory data analysis endeavor aimed at unraveling the intricate web of factors influencing ticket prices within the Indian aviation landscape. Through this analysis, I endeavor to shed light on various pertinent aspects such as the abundance of flight options available across India, the distribution of ticket availability across different classes, and the spectrum of price ranges observed within each class. By delving into these nuances, I aspire to gain deeper insights into the underlying mechanisms shaping the aviation market in India.


## About the features of cleaned dataset are explained below:

1) Airline: The airline column contains the name of the airline firm. There are six different airlines, making it a category trait.
2) Flight: The flight code of the aircraft is stored in flight.
3) Source City: City where the flight departs from is a classification feature with 6 distinctive cities.
4) Departure Time: This is a categorical feature that was deduced from time periods being divided into bins. It has six different time labels and stores information about the departure time.
5) Stops: A category feature that holds the number of stops between the source and destination cities and has 3 different values.
6) Arrival Time: This derived categorical feature was developed by binning time intervals. It maintains information regarding the arrival time and has six different time labels.
7) Destination City: The location of the aircraft's landing. It is a classification feature with 6 distinctive cities.
8) Class: A permanent feature that shows the total number of hours needed to travel between cities.
9) Duration: A permanent feature that shows the total number of hours needed to travel between cities.
10)Days Left: The trip date is subtracted from the booking date to arrive at this derived feature.
11) Price: Information about the ticket price is stored in the target variable.

## Power BI Visualization Dashboard

Using Power BI Dashboard one can quickly get to know ticket prices between different cities flying with different airlines in different classes along with flight duration

## Conclusion

1) 'Air Asia' offers the cheapest flight tickets while flying Economy class while 'Air India' is cheapest while flying Business class.
2) Booking tickets 3-7 weeks before travel will be cheaper than buying them within 3 weeks of travel as prices rise rapidly in 2-20 days period. Tickets can be cheap when bought just 1 day before however they might not be as cheap as when bought more than 3 weeks before
3) Ticket price grow linearly with duration of flight peaking when duration of flight reaches 20 hours. However due to some outliers they again fall for for flights with duration of more than 20 hours. Relation can be approximated by 2nd degree curve
4) Flight departing late at night and arriving early morning or late at night are cheapest.
5) Flight prices increase with increase in number of stops.
6) Delhi offers the cheapest flights while Hyderabad is most expensive city to fly to
