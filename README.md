# Vehicle-Rental-OOP1

- Project Overview
- Class Diagram 

***


## Project Overview
***

### 1.1 Problem Description
In today's modern and developed society, traditional paper transactions for bus rentals have become outdated, presenting numerous drawbacks such as susceptibility to damage and prolonged processing times. To address these issues, we developed a comprehensive bus rental application. This program efficiently records essential customer details such as name, age, national identity number, and phone number. Additionally, it captures rental information, including the duration of the rental in days or hours. The application then performs all necessary calculations and displays the required information for employers, streamlining the rental process.


***

### 1.2 Application Description
Bus Rental Application Features:
1. Efficiency: Saves employers time, money, and effort in processing rentals.
2. User-Friendly Interface: Upon launching, the program welcomes visitors and presents a clear menu for selection.
3. Customer Data Entry: Users can easily input customer information, including name, age, national identity number, and phone number, along with bus rental details.
4. Dynamic Pricing: The program calculates and displays the rental price for each customer based on their input.
5. Continuous Operation: Users can exit the program by selecting the designated option in the menu. The program will continue to run, allowing for multiple transactions until the user chooses to end it.


***

### 1.3 Classes and Relations
The application will utilize three primary classes to manage its functionality:

Customer Class:
- Handles all customer-related information.
- Displays customer details: name, age, phone number, and national ID.
- Stores and reads customer information to and from a file as needed.


Bus Class:
- Manages bus-related information, including color, type, and rental price.
- Stores and reads bus information to and from a file.
- Displays relevant bus details for the user.


Rent Class:
- Facilitates the association between customer and bus information.
- Handles price calculations based on rental duration and bus type.
- Stores and reads rental information to and from a file.


This structured design ensures that the bus rental application is efficient, user-friendly, and capable of handling multiple transactions seamlessly.


***
## Class Diagram 
The class diagram you've provided outlines the relationships and attributes of the key classes in the Bus Rental application. 

<img src="https://github.com/user-attachments/assets/7a8c6cc6-93a7-4de8-99a6-5e5f4f72f649" width="600" height="360">
