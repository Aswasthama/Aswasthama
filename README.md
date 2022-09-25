- 👋 Hi, I’m @rishav kumar
- 👀 I’m interested in ...python ,sql
- 🌱 I’m currently learning ...sql,m.l
- 💞️ I’m looking to collaborate on ...m.l
- 📫 How to reach me ...rishavarya001@gmail.com

<!---
Aswasthama/Rishav is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
EDA on Hotel booking analysis


Introduction -
We were given with a hotel booking dataset.csv file. By the help of that given dataset.csv file.  we have to analyse the given data and perform EDA on given dataset.csv file.our objective is to reach on a logical as well as useful result about the rise and fall in hotel booking and how elements affecting hotel booking associate with each other.


Dataset -
This data set contains booking information for a city hotel and resort hotel. It includes information such as type of the hotel, how many time it is cancelled, lead time, arrival date & month, stays in weekend nights, stays in week nights, children, adults, babies, country, market segment, distribution channel, is it repeated guest, previous cancellation, previous bookings, reserved room type, agent, company, customer type, required car parking & reservation status etc.

Understanding the whole dataset with help of column names. Given below is clearly mentioned.

hotel : Name of hotels

is_canceled : Indicating the booking was cancelled (1) or not cancelled (0)

lead_time : Number of days that elapsed between the entering data of booking

arrival_date_year : Year of arrival date


arrival_date_month : Month of arrival date

arrival_date_week_number : week number of year of arrival

arrival_date_day_of_month : Day of arrival date

stays_in_week_nights : The number of weekend nights ( saturday and sunday ) the guest stayed in hotel

stays_in_week_nights : Number of week days ( monday to friday )the guest stayed in hotel

adults : Number of adults stayed in hotel

children : Number of children stayed in hotel

babies : Number of babies stayed in hotel

meal : type of meal booked by customers

country : country of origin

market_segments : 'TA' means travel agent and 'TO' means team operators

distribution_channel : Booking distribution channel

is_repeated_guest : Repeated guest (1) or not repeated guest (0)

previous_cancellations : Number of booking that were cancelled by customers

previous_bookings_not_canceled : Number of bookings that were not cancelled by customers

reserved_room_type : Code is represented by room whic is booked by customer

assigned_room_type : code is type of room assigned to the booking

booking_changes : Number of charges made to the booking

deposit_type : Indicates on the customer made a deposit to guarantee the booking

agent : ID for travel agency

company : Company ID entity that made booking or responsable for booking payment

days_in_waiting_list : Number of days from booking to conformation booking

customer_type : booking assuming for four categories

adr : Average daily rate sum of all loading transactions dividing by total number of staying nights

required_car_parking_spaces : Car parking space required by customer

total_of_special_requests : Total special requsts made by customer

reservation_status : Reservation status, assuming in three categories

reservation_status_date : Date of the last status was set




Data cleaning –

detecting duplicate. 
Handled null values 
Null values column name company  is dropped.
Null values in column name country were replaced by ‘others’.
Null values in columns names agent and children  were replaced by ‘0’.
Detecting outliers


Questions performed in EDA  - 
Which hotel is most preferred by customers?
Which month visitors visit highly?
Which type of room highly booked and preferred by customers?
Which year got a best sales?
Which hotels mostly cancelled by the customers?
Which type of customers highly visited on both hotels?
What is percentage of repeated guest?
What is the percentage distribution of deposit type?


Libraries and tools used in EDA -
Pandas
Numpy
Seaborn
Matplotlib


Graphs & plots been used  -
Count plot
Pair-plot
Heat map
Box plot
Dist plot
Pie chart



Challenges faced – 
Huge amount of data was present in dataset.
Dealt with some missing values.
Huge amount of null values were present in dataset.
Faced difficulties in understanding the data.


Final outcome (Result) -
 We learnt
Guest mostly preferred city hotel because city hotel has maximum bookings.
August is one of the month got high amount of visitors.
Code ‘A’ room are most preferred by customers because code ‘A’ room is highly booked by customers.
In 3 years of data we got to know sales of year 2016 are higher than year 2015 & 2017.
 City hotel is mostly cancelled by the customers after booking.
Transient type of customer highly visited in both hotels.
3.2% of customers are repeated guest.
87.6%  of data is distributed in deposit type.


Conclusion –
We analyzed the entire hotel booking dataset. we covered a range of factors affecting the hotel booking. we estimated the cancellation rates, booking ratios according to months. most preferred hotels, most preferred type of room. Percentage of repeated guests. And the time when they have highest and lowest numbers of visitors by Exploratory data analysis. We also tried to predict that whether a hotel is likely to receive a disproportionately high number of guests. 
