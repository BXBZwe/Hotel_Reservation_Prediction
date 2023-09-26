# Hotel Reservations Classification Problem

## Problem Description

The online hotel reservation industry has revolutionized booking possibilities and customer behavior. However, a significant number of hotel reservations are canceled or result in no-shows, which can be challenging for hotels to manage. These cancellations can occur for various reasons, such as changes in plans or scheduling conflicts. While offering flexible cancellation policies benefits guests, it poses revenue challenges for hotels.

The goal of this project is to predict whether a customer will honor their hotel reservation or cancel it. By leveraging machine learning models, we aim to help hotels optimize their reservation management and reduce revenue loss due to cancellations.

## Dataset Overview

- **Booking_ID**: Unique identifier for each booking.
- **no_of_adults**: Number of adults.
- **no_of_children**: Number of children.
- **no_of_weekend_nights**: Number of weekend nights (Saturday or Sunday) the guest stayed or booked to stay at the hotel.
- **no_of_week_nights**: Number of week nights (Monday to Friday) the guest stayed or booked to stay at the hotel.
- **type_of_meal_plan**: Type of meal plan booked by the customer.
- **required_car_parking_space**: Whether the customer requires a car parking space (0 - No, 1 - Yes).
- **room_type_reserved**: Type of room reserved by the customer.
- **lead_time**: Number of days between the date of booking and the arrival date.
- **arrival_year**: Year of arrival date.
- **arrival_month**: Month of arrival date.
- **arrival_date**: Date of the month.
- **market_segment_type**: Market segment designation.
- **repeated_guest**: Whether the customer is a repeated guest (0 - No, 1 - Yes).
- **no_of_previous_cancellations**: Number of previous bookings canceled by the customer prior to the current booking.
- **no_of_previous_bookings_not_canceled**: Number of previous bookings not canceled by the customer prior to the current booking.
- **avg_price_per_room**: Average price per day of the reservation (in euros).
- **no_of_special_requests**: Total number of special requests made by the customer.
- **booking_status**: Flag indicating if the booking was canceled or not.

## Models Used

I explored various machine learning models to solve this classification problem:

1. Random Forest
2. Neural Network
3. Decision Tree
4. Naive Bayes
5. Support Vector Machine (SVM)

## Results

Among the models tested, the ** Random Forest model** yielded the best results in terms of predictive accuracy. It achieved an accuracy of 90%, outperforming the other models.

## Kaggle Competition

You can find the Kaggle competition associated with this problem at the following link:

[Kaggle Hotel Reservations Classification Dataset](https://www.kaggle.com/datasets/ahsan81/hotel-reservations-classification-dataset)

Feel free to explore the dataset and contribute to the competition.

