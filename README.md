# Physician Patient Booking Optimization

This project focuses on optimizing a physician's daily patient bookings to minimize revenue loss caused by no-shows. The objective is to determine how many patients a physician should book to maintain a busy schedule, considering that only 75% of the scheduled patients show up.

## Problem Overview

- The physician's normal workload is 30 patients per day.
- Due to a 25% no-show rate, only 75% of the scheduled patients actually show up for their appointments.
- The goal is to calculate the ideal number of patient bookings required to ensure a full schedule.

## Approach

### Intuitive Calculation
Using Python, we calculate the required number of bookings to compensate for the no-shows using a binomial distribution model.

### Binomial Distribution
The model assumes that 75% of scheduled patients will attend, and we calculate the necessary bookings to account for the no-show rate.

### Visualization
The results are visualized using a normal distribution curve to better understand the required bookings.

## Results

- The code will print the number of bookings the physician should schedule per day to maintain their workload considering the no-show rate.
- A visual representation using a normal distribution will also be displayed.

## Conclusion

By following this method, the physician can optimize their daily booking schedule to account for patient no-shows, thereby minimizing lost revenue and ensuring they remain productive throughout the day.








