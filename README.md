Car Rental System (Console-Based C++)
Project Overview

This is a console-based Car Rental System written in C++. Users can:

View available cars
Rent a car
Return a rented car
Exit the program

The system uses classes, vectors, and basic control structures to manage car information.

Features
Display all cars with ID, brand, model, price per day, and availability status
Rent a car by entering its ID
Return a rented car by entering its ID
Simple menu-driven interface for easy navigation
Technologies
Language: C++
Libraries Used:
<iostream> for console input/output
<vector> for storing cars
<string> for car details
Getting Started
Requirements
C++ compiler (e.g., g++, Visual Studio, Code::Blocks)
Steps to Run
Clone or download the repository.
Compile the CarRentalSystem.cpp file:
g++ CarRentalSystem.cpp -o CarRentalSystem
Run the program:
./CarRentalSystem   # Linux/Mac
CarRentalSystem.exe # Windows
Usage
On running the program, a menu will appear:
===== Car Rental System =====
1. Display all cars
2. Rent a car
3. Return a car
4. Exit
Enter the number corresponding to your choice.
Follow on-screen prompts to rent or return cars.
Repeat until you choose to exit.
Sample Cars Included
ID: 1, Brand: Toyota, Model: Corolla, Price per Day: $50, Status: Available
ID: 2, Brand: Honda, Model: Civic, Price per Day: $55, Status: Available
ID: 3, Brand: Ford, Model: Mustang, Price per Day: $100, Status: Available
ID: 4, Brand: BMW, Model: X5, Price per Day: $150, Status: Available
ID: 5, Brand: Audi, Model: A4, Price per Day: $120, Status: Available
Project Scope / Future Enhancements
Calculate rental cost based on number of days
Add customer information
Save car inventory and rental history to a file
Search or filter cars by brand, model, or price
