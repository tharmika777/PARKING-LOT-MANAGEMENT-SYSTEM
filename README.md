🚗 Parking Lot Management System

A menu-driven Java application designed to simplify parking lot management by allocating parking slots, tracking vehicle entry and exit, calculating parking fees, and displaying slot availability.

📌 Project Overview

Manual parking management can lead to delays, confusion about available spaces, and difficulties in tracking vehicle movements. This project provides a simple software-based solution using Java and Object-Oriented Programming (OOP) concepts.

🎯 Objectives

- Register vehicle numbers and vehicle types.
- Automatically allocate available parking slots.
- Track vehicle entry and exit times.
- Calculate parking fees based on parking duration.
- Search for parked vehicles and display slot availability.
- Prevent duplicate vehicle entries and handle a full parking lot.
- Validate user input and handle errors.

✨ Features

- Vehicle Management: Store vehicle details such as registration number and type.
- Automatic Slot Allocation: Assign an available parking slot to each vehicle.
- Parking Records: Maintain ticket details, including slot number and entry/exit times.
- Fee Calculation: Calculate parking charges using an hourly rate.
- Vehicle Search: Find vehicles currently parked in the lot.
- Slot Management: Release slots when vehicles exit.
- Exception Handling: Handle invalid inputs, duplicate entries, and unavailable slots.
- Parking Receipt: Display parking details and the calculated fee.

🛠️ Technologies Used

- Programming Language: Java
- Core Concepts: Object-Oriented Programming (OOP)
- Collections: ArrayList
- Date and Time: Java Date-Time API
- Exception Handling: try-catch
- Development Tools: JDK 21 or another compatible JDK, and a Java IDE or terminal

🏗️ Project Structure

The application is designed around the following classes:

Class| Responsibility
"ParkingLotApp"| Main method and menu management
"Vehicle"| Stores vehicle number and type
"ParkingSlot"| Maintains parking slot status
"ParkingTicket"| Stores ticket and parking session details
"FeeCalculator"| Calculates parking charges
"ParkingLotManager"| Manages slot allocation, searching, and records
"ReceiptPrinter"| Displays parking information and receipts

⚙️ How It Works

1. The application displays a menu of parking operations.
2. The user selects an operation.
3. For vehicle entry, the application validates the vehicle details.
4. An available parking slot is assigned to the vehicle.
5. The entry time and parking details are recorded.
6. When the vehicle exits, the parking duration and fee are calculated.
7. The parking slot is released, and the receipt and updated slot status are displayed.

💰 Sample Fee Calculation

For example, if the parking duration is 95 minutes and the hourly rate is ₹30:

- Parking duration: 95 minutes
- Billing duration: 2 hours
- Hourly rate: ₹30
- Total parking fee: ₹60

The sample calculation rounds the duration up to the next full hour.

▶️ How to Run

Prerequisites

Install a compatible Java Development Kit (JDK) and ensure that "java" and "javac" are available in your terminal.

Compile and Run

1. Clone the repository:
   
   git clone <your-repository-url>

2. Navigate to the project directory:
   
   cd <your-project-folder>

3. Compile the Java source files:
   
   javac *.java

4. Run the main class:
   
   java ParkingLotApp

Note: The commands above assume that all Java source files are in the same directory and that the main class is named "ParkingLotApp". Adjust the commands if your project uses packages or a different folder structure.

🧪 Testing

The application should be tested for the following cases:

- Valid vehicle registration and slot allocation.
- Attempting to park when all slots are occupied.
- Entering a duplicate vehicle number.
- Providing invalid menu choices or empty vehicle details.
- Attempting to exit a vehicle that is not parked.
- Calculating the parking fee and releasing the slot after exit.

🌍 Applications

- College and university parking facilities.
- Shopping centres and commercial buildings.
- Office parking management.
- Hospital parking areas.
- Residential apartment complexes.

🚀 Future Enhancements

- Database integration for persistent parking records.
- Graphical user interface (GUI).
- QR-code-based parking tickets.
- Digital payment integration.
- Real-time parking sensors and automated entry barriers.

📚 Learning Outcomes

- Understanding Java classes, objects, and encapsulation.
- Working with collections and conditional statements.
- Applying exception handling and input validation.
- Managing date and time calculations.
- Developing and testing a practical Java application.

👩‍💻 Project Information

- Project: Parking Lot Management System
- Type: Individual Mini Project
- Course: Java Programming
- Academic Year: 2026–2027

---

This project is developed for educational purposes as a basic parking management simulation.
