# 🚗 Car Rental System

A simple **Java-based Car Rental System** that allows users to rent and return cars through a menu-driven console application. The system manages car details, customer information, and rental operations.

## 📌 Overview

The Car Rental System is a console-based application developed using Java. It provides a simple interface for customers to rent available cars, specify rental duration, and return rented vehicles.

This project demonstrates core Java programming concepts, object-oriented programming, and basic application logic.

## ✨ Features

- **Menu-Driven Interface:** Simple console-based navigation.
- **Rent a Car:** Enter customer details and select a car for rental.
- **Return a Car:** Provides an option to return a rented vehicle.
- **Car Availability:** Displays available cars with their IDs and names.
- **Rental Duration:** Accepts the number of days for a rental.
- **Input Validation:** Handles invalid menu choices and car selections.

## 🛠️ Technologies Used

- Java
- Object-Oriented Programming (OOP)
- Java Scanner for user input
- Command-Line Interface (CLI)

## 📂 Project Structure

```text
Car-Rental-System/
├── src/
│   ├── Main.java
│   ├── Car.java
│   ├── CarRentalSystem.java
│   ├── Customer.java
│   └── Rental.java
├── .gitignore
└── README.md
```

*Note: The exact file structure may vary depending on your local project setup.*

## ⚙️ Prerequisites

Before running the project, make sure you have:

- Java Development Kit (JDK) installed.
- Visual Studio Code or another Java-compatible IDE.
- A terminal such as PowerShell or Command Prompt.

Check your Java installation:

```powershell
java -version
javac -version
```

## 🚀 How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/samgupta221/Car-rental-system.git
```

### 2. Navigate to the Source Directory

```bash
cd Car-rental-system/Car-Rental-System/src
```

If your cloned repository contains `src` directly in its root, use:

```bash
cd Car-rental-system/src
```

### 3. Compile the Java Files

```bash
javac *.java
```

### 4. Run the Application

```bash
java Main
```

## 💻 Sample Output

```text
===== Car Rental System =====
1. Rent a Car
2. Return a Car
3. Exit
Enter your choice: 1

== Rent a Car ==

Enter your name: sam

Available Cars:
C001 - Toyota Camry
C002 - Honda Accord
C003 - Mahindra Thar

Enter the car ID you want to rent: C002
Enter the number of days for rental: 2
```

*Note: The sample shows the expected format of a rental interaction. Successful rental depends on the application's validation and availability logic.*

## 📖 How It Works

1. The application displays a menu with options to rent a car, return a car, or exit.
2. The customer selects an operation.
3. For a rental, the customer enters their name.
4. The system displays the available cars and asks for a car ID.
5. The customer specifies the rental duration.
6. The system validates the selection and processes the rental if the car is available.

## 🎯 Learning Outcomes

- Understanding Java classes and objects.
- Applying object-oriented programming principles.
- Working with arrays or collections and application logic.
- Accepting and validating console input.
- Implementing basic car rental workflows.

## 🔮 Future Improvements

- Add a graphical user interface or web interface.
- Integrate MySQL for persistent data storage.
- Calculate rental charges automatically.
- Add customer and rental history management.
- Improve input validation and error handling.
- Add user authentication and administrative features.

