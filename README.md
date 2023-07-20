# Hotel_Booking_Analysis
Objective:
The Hotel Booking dataset contains booking details for city and resort hotels, including
booking time, stay duration, number of adults, children/babies, and available parking
spaces. The main goal is to conduct EDA on the dataset to uncover general trends in hotel
bookings and understand how various factors interact in influencing bookings. By analyzing
booking patterns over time, peak seasons, and correlations between variables like the 
number of adults and length of stay, we aim to draw valuable insights for hotel management 
and marketing strategies. Understanding these interactions can lead to better decision-
making and improving guest experiences.

Dataset:
The dataset provided contains booking information for both a city hotel and a resort hotel.
It includes various features such as hotel name, booking cancellation status, lead time, arrival
date details, length of stay, number of adults, children, and babies in the booking, meal type, 
customer's country of origin, market segment, booking medium, whether the guest is a 
repeated customer, previous cancellation, and non-cancellation history reserved and 
assigned room types, booking changes, deposit type, agent and company IDs, waiting list 
duration, customer type, average daily rate, requested car parking spaces, total special 
requests, reservation status, and reservation status date.

The primary objective is to perform Exploratory Data Analysis (EDA) on this dataset to 
identify general trends in hotel bookings and understand how different factors interact to 
influence booking patterns. Through this analysis, we aim to gain valuable insights for 
hotel management and improve customer experiences.

Tools and Libraries Used:
We have used Python 3 for its following packages:

1. Pandas
2. Numpy
3. Matplotlib
4. Seaborn
5. Folium
6. plotly Express

Data Cleaning and Feature Engineering:

(1) Removing Duplicate rows:

All duplicate rows were dropped.

(2) Handling null values:

Null values in columns company and agent were replaced by 0.
Null values in column country were replaced by others.

(3) Converting columns to appropriate data types:

Changed data type of children, company, and agent to int type.

(4) Creating new columns:

Created a new column total_stay by adding stays_in_weekend_nights+stays_in_week_nights.
Created a new column total_people by adding adults+children+babies.

Exploratory Data Analysis:

Exploratory Data Analysis is done on the below-mentioned categories:-

Univariate Analysis

Hotel wise Analysis

Distribution channel-wise Analysis

Booking cancellation Analysis

Customer Centric Analysis

Conclusion:

City Hotel is most preferred by guests and thus city hotels have got a maximum number of bookings. So from a business perspective, we should target those months between May to Aug.

In the case of city hotels, months with high bookings (May, June, September, October) witnessed more cancellations.

Guest numbers for the Resort hotel go down slightly from June to September though variations in bookings and cancellations are less in the case of resort hotels.

Both hotels have the fewest guests during the winter.

Most of the bookings we have received are from TA/TO and the least booking we have received from Corporate.

Since 98.7 % of the guests prefer an A deposit type of stay. The high rate of cancellations can be due to high no-deposit policies.

The most common stay length is less than 4 days and generally, people prefer city hotels for a shorter stay, but for a longer stay resort hotel is preferred. Resort hotel has a slightly high avg lead time which means customers plan their trips very early.

Resort hotel has a higher retention rate compared to city hotel which means customers are willing to stay again in resort hotel but the retention rate for city hotel is 3.20% and for resort hotel is 5.03% which is very less. The most preferred Room type is "A". most preferred meal is BB(Bed & Breakfast) while HB(Half-Board) and SC(Self Catering) are equally preferred.93.8 % of guests did not require a parking space and only 6.2 % of guests required only 1 parking space.

City hotel has significantly longer waiting time than a resort hotel, hence city Hotel is much busier than Resort Hotel. Also, City hotels have a slightly high avg lead time than resort hotels. Thus, city hotel makes slightly more revenue than resort hotel. The City Hotel has more guests during spring and autumn, when the prices are also highest, In July and August there are fewer visitors, although prices are lower. Thus, customers can get good deals on bookings in July and August in city hotels.

Cancellations are high when done through agents compared to direct bookings. Hotels need to do marketing and give special incentives for direct bookings as these may establish personal one-to-one relationships promoting customer loyalty.

Guest numbers for the Resort hotel go down slightly from June to September, which is also when the prices are highest. Thus, these months should be avoided for bookings.

We have a huge number of visitors from western Europe, namely Portugal, the UK and France being the highest. We can instruct the marketing team to target people from this region.

The highest Booking received by the hotels is through TA/OT so they are one of the most trusted booking providers. Also Direct booking count is greater than the GDS system so still customer does not have complete faith in online booking platforms.

The average daily rate is more in the Resort hotel than City Hotel. Prices in the Resort Hotel are much higher during the summer and prices of city hotel varies less and is most expensive during Spring and Autumn.

Those who were not assigned the same room as reserved do not affect adr. From the pie chart, we can analyze that only 5.39% of guests canceled their reservation after assigning different rooms.

2016 seems to be a year where hotel booking is at its highest and it seems the summer period is a peak for hotel booking. The trend for the arrival day of month has been roller coaster.

The majority of the stays are over the weekday night so the target should be given and on the other day of the month it was random.

Challenges Faced:

There was a lot of duplicate data.

Data was present in wrong datatype format.

Choosing appropriate visualization techniques to use was difficult.

A lot of null values were there in the dataset.
