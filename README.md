# Car Rental System

This repository contains a Java implementation of a simple car rental system. The system allows users to rent and return cars, providing basic functionalities for managing rentals and customer interactions.

# Features
Rent a Car: Users can rent available cars by providing their name, selecting a car from the available options, and specifying the rental duration.

Return a Car: Users can return a rented car by providing the car ID.

Error Handling: The system provides error messages for invalid inputs and unavailable cars.

Rental Pricing: The system calculates the total price based on the rental duration and the base price per day of the selected car.

Simple Interface: Users interact with the system through a command-line interface.

# Classes
Car: Represents a car object with properties such as ID, brand, model, base price per day, and availability status.

Customer: Represents a customer with a unique ID and name.

Rental: Represents a rental transaction, linking a car to a customer and specifying the rental duration.

CarRentalSystem: Implements the main functionalities of the car rental system, including adding cars and customers, renting and returning cars, and providing a user interface through the menu method.

Main: Entry point of the program containing the main method to start the car rental system.

# Usage

Setup: Clone the repository to your local machine.

Compile: Compile the Java files using a Java compiler. You can use any Java IDE or the command line.

Run: Execute the compiled Main class to launch the car rental system.

Menu Navigation: Follow the prompts in the command-line interface to rent or return cars.
