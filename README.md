# ElectroCharge Pro: Intelligent EV Charging Station Locator and Reservation

## Abstract
ElectroCharge Pro simplifies booking and managing EV charging stations. Developed in Java using JavaFX, the MVC framework, data structures, and MySQL, this desktop application enables users to locate and reserve charging stations in advance by entering their source and destination locations.

## Introduction
The rise in electric vehicles (EVs) necessitates robust charging infrastructure. This project aims to mitigate range anxiety by providing real-time data on charging station locations, availability, and booking options.


## Problem Statement
Despite the rise in EV adoption, the lack of dependable infrastructure for finding and accessing charging stations remains a barrier. ElectroCharge Pro addresses this by offering queue management, availability information, and efficient trip planning.

## Objectives
- Develop a user-friendly interface for booking EV charging stations.
- Implement real-time status updates.
- Integrate secure user registration and authentication.
- Efficiently store and retrieve data using MySQL.
- Apply the MVC architectural pattern for maintainable code.

## Methodology

### Project Architecture
- **MVC Framework**:
  - **Model**: Business logic and data processing, including MySQL database interaction.
  - **View**: User interface developed using JavaFX.
  - **Controller**: Handles user input, processes requests, and updates the View.

### Database Integration
MySQL stores information about EV stations, user accounts, and bookings. JDBC is used for database operations.

### Data Structure and Algorithm
- **Data Structure**:
  - Java Collections (ArrayLists) store state, city, and address data for ComboBoxes.
- **Algorithm**:
  - The MVC pattern separates application components to improve organization and scalability.

## Project Features
- **User Registration and Authentication**: Secure account creation and login, with hashed passwords stored in the database.
- **EV Station Booking**: Search for and book available charging stations based on location.
- **Real-time Status Updates**: View real-time station availability and waiting times.
- **User-friendly Interface**: Intuitive UI developed with JavaFX.

## Technical Implementation
- **JavaFX for GUI Development**: Interactive frontend with ComboBoxes, TextFields, Buttons, and Alerts.
- **MySQL Database Integration**: Data storage and retrieval with JDBC.
- **MVC Framework Structure**: Organized code with data processing in the Model, UI in the View, and user input handling in the Controller.
- **Data Access and Manipulation**: Data validation and error handling ensure integrity and stability.

## Conclusion
ElectroCharge Pro aims to enhance the EV user experience by providing a reliable, user-friendly platform for locating and reserving charging stations. This project addresses the key challenges of EV adoption by reducing range anxiety and ensuring easy access to charging infrastructure.
