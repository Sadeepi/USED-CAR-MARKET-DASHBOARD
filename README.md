# **USED CAR MARKET DASHBOARD**
## Dashbord for used car market in India</br>

We used different plots like pie charts, box plots, bar charts, scatter charts, heatmaps and histograms. Python libraries like dash, plotly, numpy and pandas are used. This is the first five records of the dataset. 

## Data Cleaning
According to this screenshot power,engine and mileage are with units. 

![Capture20](https://github.com/Sadeepi/Dashboard/assets/86165230/840d9976-fae9-492d-9c3c-bec51d55058c)


Engine, power, seats and new price have missing values. 

![Capture21](https://github.com/Sadeepi/Dashboard/assets/86165230/6d0368bb-91e4-4e0e-9dbd-bf9ed5b7bfb2)

Removing units in Engine and Power

![Capture22](https://github.com/Sadeepi/Dashboard/assets/86165230/19b9ab84-5ea6-44a4-9fb5-35e4d43d01ff)

We drop the New prices column. Missing values in the seats column filled with the median of the seats column. Converted engine and power columns into numerical data type. Missing values in engine and power columns filled with their missing vlaues. 

![Capture23](https://github.com/Sadeepi/Dashboard/assets/86165230/b1c930c1-42f5-4d99-af95-db3f8e40fc9d)

This is a screenshot of the dashboard we created. 

![Capture11](https://github.com/Sadeepi/Dashboard/assets/86165230/bf0fda27-bebb-4360-b3ed-da1a0a3d9f06)


Pie chart was used to visualize the transmission type of the cars. According to the pie chart most of the cars are manual cars.

![Capture1](https://github.com/Sadeepi/Dashboard/assets/86165230/03b730fc-ab5c-4dbd-bd26-f54b63a4c935)
##
This grouped box plot visualize the car price of each owner type and each transmission types (manual and automatic). According to the box plot most of the cars having higher prices are first owned cars. Car prices of fourth & above owner type are relatively low. 

![image](https://github.com/Sadeepi/Dashboard/assets/86165230/a0946b70-7ccc-40bd-bd09-eeb96698cef3)
##
'seats vs prices' grouped box plot visualize the how prices change with number of seats. Car with highest price has five seats. 

![Capture3](https://github.com/Sadeepi/Dashboard/assets/86165230/aff84690-004c-4a91-8958-0e5bb48e3b78)
##
we used this plot to visualize the distribution of Kilometers_Driven, Price, Power, Engine and Year. To visualize all categories using one plot we used radio buttons. </br>

This dataset includes cars manufactured in between 1998 and 2019. Highest number of cars were manufactured in 2014. This is a left skewed distribution. 

![Capture4](https://github.com/Sadeepi/Dashboard/assets/86165230/b462151b-5556-4292-b73c-d79c5d963a4f)

Most of the cars' price is less than 50 Indian rupees. This is a right skewed distribution. 

![Capture5](https://github.com/Sadeepi/Dashboard/assets/86165230/8d0b34ef-b7e6-4ca8-88d3-0d1b4c28a7f0)
##
According to the distribution for Engine most of the cars have less than 2000 CC engine capacity. 
![Capture6](https://github.com/Sadeepi/Dashboard/assets/86165230/5dd434d9-9136-4f06-bb3c-23439ece26bf)
##

Almost all the cars have driven less than 2M kilometres. 

![Capture7](https://github.com/Sadeepi/Dashboard/assets/86165230/895f2058-220c-4bd8-a724-1ff803f1f79e)
##
Most of the cars are first owned cars. Nearly 1000 number of cars are second owned cars. 

![Capture12](https://github.com/Sadeepi/Dashboard/assets/86165230/a2043b7e-c55b-498a-a35d-8b1078db692a)
##

According to the stacked bar chart highest number of used cars in Mumbai. Highest number of used cars are  in Hyderabad. Less number of used cars are in Ahmedabad. Number of manual used cars are higher than number of automatic cars in all districts. 

![Capture13](https://github.com/Sadeepi/Dashboard/assets/86165230/af77f6a3-f56e-437e-a6d6-31ab3780e697)
##
This heatmap visualize the relashionship between two continuous variables. Engine and price has positive relashionship. 

![Capture14](https://github.com/Sadeepi/Dashboard/assets/86165230/eb1f7b96-4e61-4968-bb80-dbe7f165137e)

##

This pie chart shows the percentage of each car type located in each district. Users can select the car type uising a dropdown. 

![Capture15](https://github.com/Sadeepi/Dashboard/assets/86165230/74a1e68f-927a-494f-bf69-cab2ebc34549)
##

This scatter plot shows the relasionship between price and power. According to the scatter plot when power increases, the price of the used cars gets the increase.

![Capture16](https://github.com/Sadeepi/Dashboard/assets/86165230/e969bedb-5ad4-4f04-8e71-8826d32c4dd7)
##

This scatter plot shows the relasionship between price and Kilometers_Driven. 

![Capture17](https://github.com/Sadeepi/Dashboard/assets/86165230/c0c5851f-9197-4f6e-bf67-00ac681a98d0)

##
This scatter plot shows the relasionship between price and engine. 

![Capture18](https://github.com/Sadeepi/Dashboard/assets/86165230/fee8cd5a-1088-4185-adcc-fc08b8a90599)
##
This scatter plot shows the relasionship between price and year. With the time used car price became increase. 

![Capture19](https://github.com/Sadeepi/Dashboard/assets/86165230/ea811509-fc67-4cf1-b062-2f31e8589696)

##







