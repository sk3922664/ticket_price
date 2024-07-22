# Airlines Ticket Price Analysis

## Objective

As an aviation enthusiast, I always look forward to flying whenever I plan to travel. Since the Covid-19 pandemic ended, aviation market began to recover slowly from rock bottom ticket prices in peak of pandemic. With the war in Ukraine and rise in ATF prices, ticket prices have been through the roof reaching new high. As a result of this, I decided to do an exploratory data analysis for ticket prices to better understand the factors affecting them in India.
I aim to answer questions like No. of flights available across India, Ticket availability across different class, Price range across different class, etc.

## About the dataset

Data is gathered from the Kaggle and considered as secondary data.
The dataset includes details on the ticket booking alternatives available through the website "Easemytrip" for flights between India's top 6 metro areas. The cleaned dataset contains 11 characteristics and 300261 datapoints. Data was gathered in two stages: for business class tickets and for economy class tickets. The site provided a total of 300261 unique flight booking possibilities. 50 days of data were gathered, from February 11 to March 31 of 2022. 
Dataset Link: [Kaggle](https://www.kaggle.com/datasets/shubhambathwal/flight-price-prediction)

The various features of the cleaned dataset are explained below:
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
