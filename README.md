# Hotel Booking Analysis — Understanding Booking & Cancellation Behaviour

Exploratory data analysis of a hotel booking dataset (2017–2019, ~119K bookings) answering three business questions: which hotel type is booked most often, how stay duration affects cancellation, and how lead time affects cancellation. Built with Python, Pandas, and Matplotlib/Seaborn in a Jupyter Notebook.

## Dataset

Hotel bookings dataset covering City and Resort hotels, 2017–2019, ~119,390 rows and 29 columns, including booking dates, stay length, lead time, cancellation status, and guest details.

## Key Findings

- **Hotel type:** City Hotel is booked roughly twice as often as Resort Hotel (66.4% vs. 33.6%), and both types share the same seasonal pattern — low January–March, peaking September–October.
- **Stay duration:** City Hotel cancellation rate climbs sharply with longer stays (42.7% → 67.1% from 0–3 to 10+ nights), while Resort Hotel stays stable (24–32%) regardless of stay length.
- **Lead time:** City Hotel bookings made 180+ days in advance cancel 64.1% of the time — the single highest-risk segment found in the analysis, driving the project's main recommendation (deposits for far-ahead City Hotel bookings).

## Notebook

- [Full notebook (HTML export)](notebooks/Hotel_Business_using_Data_Visualization.html)
- [Notebook source (.ipynb)](notebooks/hotel_booking_analysis.ipynb)
