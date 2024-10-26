# Car Rental System

## Overview
The **Car Rental System** is a console-based Java application that allows users to rent and return cars with an intuitive interface. This system maintains a list of available cars, processes rentals, and tracks the status of each car. Designed with simplicity in mind, this system provides essential rental functions for customers to manage their car rentals.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Sample Output](#sample-output)
- [License](#license)

## Features
- **Car Management**: Easily add cars with unique IDs, brands, models, and base daily rental prices.
- **Customer Management**: Add customers by their names and assign unique customer IDs.
- **Rent a Car**: Rent an available car for a specified number of days, with a generated total price.
- **Return a Car**: Return a rented car and make it available for future rentals.
- **Interactive Menu**: Simple menu-based interface for ease of use.

## Getting Started
To run this project locally, ensure you have the following installed:

### Prerequisites
- **Java Development Kit (JDK) 8 or higher**

### Installation
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/username/car-rental-system.git
   cd car-rental-system
   ```

2. **Compile the Code**:
   ```bash
   javac Main.java
   ```

3. **Run the Application**:
   ```bash
   java Main
   ```

## Usage
1. **Renting a Car**:
   - Select the **"Rent a Car"** option from the menu.
   - Enter your name, view available cars, select a car by ID, and specify the number of rental days.

2. **Returning a Car**:
   - Select the **"Return a Car"** option from the menu.
   - Enter the car ID to return a previously rented car.

3. **Exiting the System**:
   - Select the **"Exit"** option from the menu to quit the application.

## Project Structure
- **Main.java**: Entry point for running the application.
- **CarRentalSystem**: Manages the core functionality, including adding cars, handling rentals, and maintaining car availability.
- **Car**: Represents individual car objects with attributes like brand, model, rental price, and availability.
- **Customer**: Stores customer details, including customer ID and name.
- **Rental**: Represents rental instances, associating cars with customers and rental duration.

## Sample Output
```plaintext
===== Car Rental System =====
1. Rent a Car
2. Return a Car
3. Exit
Enter your choice: 1

== Rent a Car ==

Enter your name: John Doe

Available Cars:
C001 - Toyota Camry
C002 - Honda Accord
C003 - Mahindra Thar

Enter the car ID you want to rent: C001
Enter the number of days for rental: 3

== Rental Information ==

Customer ID: CUS1
Customer Name: John Doe
Car: Toyota Camry
Rental Days: 3
Total Price: $180.00

Car rented successfully.
```

## License
This project is licensed under the MIT License.
