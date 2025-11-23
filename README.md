# Truck-Buyback-Estimator

Python program that simulates a used-truck purchasing service.  
The user enters the model year of their truck, and the program decides whether the dealership will buy it and how much they will offer.

## How It Works

- Prompts the user for the truck's year (enter `0` to exit).
- Uses a **sentinel-controlled while loop** to keep asking for years until the user chooses to stop.
- Applies business rules:
  - Trucks **outside** the 2011–2020 range are rejected.
  - Trucks from **2011–2015** receive an offer of **$15,000**.
  - Trucks from **2016–2020** receive an offer of **$22,000**.
- Prints a thank-you message when the user finishes.

## Concepts Covered

- User input and type casting with `int()`
- Sentinel-controlled `while` loops
- Conditional logic with `if / elif / else`
- Simple business rules and output messages

## Author

Caroline Amorim Oliveira  
Valencia College Dual Enrollment – Introduction to Programming Concepts

## License

This project is licensed under the MIT License.
