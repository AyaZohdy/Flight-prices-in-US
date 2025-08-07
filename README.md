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
1. Columns
['legId', 'searchDate', 'flightDate', 'startingAirport', 'destinationAirport', 'fareBasisCode', 'travelDuration', 'elapsedDays', 'isBasicEconomy', 'isRefundable', 'isNonStop', 'baseFare', 'totalFare', 'seatsRemaining', 'totalTravelDistance','segmentsDepartureTimeEpochSeconds', 'segmentsDepartureTimeRaw', 'segmentsArrivalTimeEpochSeconds', 'segmentsArrivalTimeRaw', 'segmentsArrivalAirportCode', 'segmentsDepartureAirportCode', 'segmentsAirlineName', 'segmentsAirlineCode','segmentsEquipmentDescription', 'segmentsDurationInSeconds', 'segmentsDistance', 'segmentsCabinCode']

2. Columns we used
'travelDuration' , 'totalFare', 'totalTravelDistance', 'segmentsAirlineName', 'isBasicEconomy', 'isNonStop'

3. Missing data
We don't have missing data in our choosen columns. Only in 'totalTravelDistance' column but the missing cells to the avaliable one aren't huge to affect the results.
   
- Conclusion
Flight prices are shaped by multiple factors, including time of day, airlines, number of stops, distance, duration, and travel class. Understanding these dynamics can help travelers make smarter booking decisions and enable airlines to optimize pricing strategies more effectively.

● Dependencies: 
--
- Data Manipulation: pandas, isodate, datetime and parse_duration.
- Data Visualization: seaborn and matplotlib

