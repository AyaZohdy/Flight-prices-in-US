# Flight_prices_in_US

● Description: 
--
Traveling is one of most requesting things and people travel for several purposes like working, studying and visiting. One of travel challenging points is the price.

The aim of this project is to understand how different factors—like the airlines, travel class, number of stops, and day of the week affect flight prices. By analyzing these factors, we aim to help travelers & decision makers to make the best decisions.

● Dataset:
--
The data from (https://www.kaggle.com/datasets/dilwong/flightprices/data)

● Analysis: 
--
1. The Columns of the dataset

['legId', 'searchDate', 'flightDate', 'startingAirport', 'destinationAirport', 'fareBasisCode', 'travelDuration', 'elapsedDays', 'isBasicEconomy', 'isRefundable', 'isNonStop', 'baseFare', 'totalFare', 'seatsRemaining', 'totalTravelDistance','segmentsDepartureTimeEpochSeconds', 'segmentsDepartureTimeRaw', 'segmentsArrivalTimeEpochSeconds', 'segmentsArrivalTimeRaw', 'segmentsArrivalAirportCode', 'segmentsDepartureAirportCode', 'segmentsAirlineName', 'segmentsAirlineCode','segmentsEquipmentDescription', 'segmentsDurationInSeconds', 'segmentsDistance', 'segmentsCabinCode']

2. Columns we used
   
'legId', 'travelDuration' , 'totalFare', 'totalTravelDistance', 'segmentsAirlineName', 'isBasicEconomy', 'isNonStop', 'seatsRemaining', 'segmentsDepartureTimeRaw', 'flightDate', 'segmentsCabinCode', 'segmentsDepartureAirportCode', 'segmentsDistance'

3. Missing data
   
We don't have missing data in our choosen columns. Only in 'totalTravelDistance' column but the missing cells to the avaliable one aren't huge to affect the results.

4. Outcomes

    1. The findings show that both flight timing and availability influence ticket prices. This information can help travelers find better deals. Airlines can use these insights to improve flight scheduling and pricing decisions, matching supply with customer demand more effectively.
    2.	Prices are different between the airlines. This information shows that travelers may select the airline according to the services that they will receive from the airline and another factor like the time, stops .. etc.
    3.	In this data the duration (time of flight) and distance affect the price of ticket positively but not obviously and this information can give the decision makers hint that there are different factors affecting the prices like time and stops.
    4.	Flight class and the number of stops also affect the prices. This may be due to the destination and the duration that impact on flight price.

# - Conclusion:
--
Flight prices are shaped by multiple factors, including time of day, airlines, number of stops, distance, duration, and travel class. Understanding these dynamics can help travelers make smarter booking decisions and enable airlines to optimize pricing strategies more effectively.

● Dependencies: 
--
- Data Manipulation: pandas, isodate, datetime and parse_duration.
- Data Visualization: seaborn and matplotlib

