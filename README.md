# booking-challenge
This project aims to predict the next city the user will visit, given a previous sequence of cities visited.

# About
[Mauro Napoli](https://github.com/MauroDNapoli) and [Aneri Dand](https://github.com/aneridand) are students of MS in Data Science program at the University of San Francisco. This project is part of their Deep Learning Course (MSDS631). <br>

# Data
The dataset for this project has been sourced from [bookingchallenge.com](https://www.bookingchallenge.com/). The challenge was closed on January 28th, 2021. However, we chose this dataset in order to learn more about sequential models and their applications in a high impact business environment. <br> <br>
The training dataset consists of over a million of anonymized hotel reservations, based on real data, with the following features:
* `user_id` - User ID
* `check-in` - Reservation check-in date
* `checkout` - Reservation check-out date
* `affiliate_id` - An anonymized ID of affiliate channels where the booker came from (e.g. direct, some third party referrals, paid search engine, etc.)
* `device_class` - desktop/mobile
* `booker_country` - Country from which the reservation was made (anonymized)
* `hotel_country` - Country of the hotel (anonymized)
* `city_id` - city_id of the hotel’s city (anonymized)
* `utrip_id` - Unique identification of user’s trip (a group of multi-destinations bookings within the same trip)

# Models
For this project, we chose three architectures of recurrent neural network (RNN): <br>
1. Vanilla Recurrent Neural Network (Vanilla RNN)
2. Gated Recurrent Units (GRUs)
3. Long Short Term Memory (LSTM)

