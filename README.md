# EDA-HOTEL-BOOKING-

**PROJECT SUMMARY :-**

Have you ever wondered when the best time of year to book a hotel room is? Or the optimal length of stay in order to get the best daily rate? What if you wanted to predict whether or not a hotel was likely to receive a disproportionately high number of special requests? This hotel booking dataset can help you explore those questions! This data set contains booking information for a city hotel and a resort hotel, and includes information such as when the booking was made, length of stay, the number of adults, children, and/or babies, and the number of available parking spaces, among other things. All personally identifying information has been removed from the data. Explore and analyze the data to discover important factors that govern the bookings

**BUSINESS OBJECTIVE:-**

The core focus of our business objective is to maximize hotel bookings while minimizing cancellations, thereby ensuring a robust customer retention strategy. Our aim is to foster a loyal customer base and extend the duration of guests' stays, ultimately leading to sustained growth and success in the hospitality industry

**KNOWLEDGE ABOUT DATASET:-**

1) Total count of rows are 119390 and columas are 32.

2) Overall there are 31994 duplicated values.

3) Null values were found in columns 4 Columns -

1. Company-Missing Values will be filled with 0.
2. Agent -Missing Values will be filled with 0.
3. Country -Assuming that country was not found while entering the data so the 'Others' option was chosen by the user, missing values will be filled with the object 'Others'
4. Children -Null Value count is only 4 so we can replace it with 0 assuming no children were present.

**VARIABLE DESCRIPTION :-**

1) hotel : Hotel(Resort Hotel or City Hotel)

2) is_canceled : Value indicating if the booking was canceled (1) or not (0)

3) lead_time : Number of days that elapsed between the entering date of the booking into the PMS and the arrival date

4) arrival_date_year : Year of arrival date

5) arrival_date_month : Month of arrival date

6) arrival_date_week_number : Week number of year for arrival date

7) arrival_date_day_of_month : Day of arrival date

8) stays_in_weekend_nights : Number of weekend nights (Saturday or Sunday) the guest stayed or booked to stay at the hotel

9) stays_in_week_nights : Number of week nights (Monday to Friday) the guest stayed or booked to stay at the hotel

10) adults : Number of adults

11) children : Number of children

12)babies : Number of babies

13) meal : Type of meal booked. Categories are presented in standard hospitality meal packages:

14) country : Country of origin.

15) market_segment : Market segment designation. In categories, the term “TA” means “Travel Agents” and “TO” means “Tour Operators”

16) distribution_channel : Booking distribution channel. The term “TA” means “Travel Agents” and “TO” means “Tour Operators”

17) is_repeated_guest : Value indicating if the booking name was from a repeated guest (1) or not (0)

18) previous_cancellations : Number of previous bookings that were cancelled by the customer prior to the current booking

19) previous_bookings_not_canceled : Number of previous bookings not cancelled by the customer prior to the current booking

20) reserved_room_type : Code of room type reserved. Code is presented instead of designation for anonymity reasons.

21) assigned_room_type : Code for the type of room assigned to the booking.

22) booking_changes : Number of changes/amendments made to the booking from the moment the booking was entered on the PMS until the moment of check-in or cancellation

23) deposit_type : Indication on if the customer made a deposit to guarantee the booking.

24) agent : ID of the travel agency that made the booking

25) company : ID of the company/entity that made the booking or responsible for paying the booking.

26) days_in_waiting_list : Number of days the booking was in the waiting list before it was confirmed to the customer

27) customer_type : Type of booking, assuming one of four categories

28) adr : Average Daily Rate as defined by dividing the sum of all lodging transactions by the total number of staying nights

29) required_car_parking_spaces : Number of car parking spaces required by the customer

30) total_of_special_requests : Number of special requests made by the customer (e.g. twin bed or high floor)

31) reservation_status : Reservation last status, assuming one of three categories

32) Canceled – booking was canceled by the customer.
33) Check-Out – customer has checked in but already departed
34) No-Show – customer did not check-in and did inform the hotel of the reason why
35) This variable can be used in conjunction with the ReservationStatus to understand when was the booking canceled or when did the customer checked-out of the hotel

**SOLUTION TO BUSINESS OBJECTIVE :-**

1. Focusing more on direct bookings - Hotel's website plays a crucial role. It must have a strong digital identity to attract maximum visitors. Your hotel website should be visually attractive, easy to navigate and above all it should be user-friendly.

2. Promoting good reviews of websites. - Good reviews can influence a traveller’s booking decision in a big way. This is why it is paramount to strategically position and promote positive guest reviews on thewebsite. It should be visible throughout all the pages till a visitor is done with the whole booking process.

3. Entice your website visitor with offers or freebies. - Once visitors are on your website, you can give them compelling reasons to book directly with you. Clearly mention the kind of perks they are entitled to if they make direct bookings.

4. Choosing the most profitable distribution channels.

5. Identifying and targeting the most profitable guests.Also taking feedbacks can really help to meet the customer satisfaction.

6.Advance Meal Preparation: Maintain raw materials for BB (Bed and Breakfast) meals in advance to ensure timely service.

7.Increase City Hotel Capacity: Expand the number of rooms in City Hotels to reduce waiting times and accommodate more guests.

8.Market Segment Offers: Run promotions targeted towards other market segments to increase bookings from those segments.

9.Manage Waiting Times: Focus on optimizing operations in City Hotels to reduce waiting times and improve guest experience.

**CONCLUSION :-**

We’ve drawn many inferences from the survey. Here’s a summary of a few of them:

1. City hotels are the most preferred hotel type by the guests. We can say City hotel is the busiest hotel.

2. Repeated guests do not cancel their reservations. Of course there are some exceptions. Also most of the customers are not repeated guests.

3. 27.5 % bookings were got cancelled out of all the bookings whereas 72.48% bookings were not cancelled.

4. Only 3.9 % people were revisited the hotels. Rest 96.1 % were new guests. Thus retention rate is low.

5. BB( Bed & Breakfast) is the most preferred type of meal by the guests.

6. Average ADR for city hotel is high as compared to resort hotels. These City hotels are generating more revenue than the resort hotels.

7. Booking cancellation rate is high for City hotels which almost 30 %.

8. Waiting time period for City hotel is high as compared to resort hotels. That means city hotels are much busier than Resort hotels

9. The 'A' room type is most popular choice among the travellers which is followed by room 'D' type.

10. To ensure guest loyalty, a well-structured loyalty points program can be implemented, encouraging guests to return for future stays
