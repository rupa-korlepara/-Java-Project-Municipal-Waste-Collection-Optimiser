# Municipal Waste Collection Optimiser

##  Project Overview

The **Municipal Waste Collection Optimiser** is a Java-based application designed to improve the efficiency and organisation of municipal waste collection. The system prioritises waste bins based on their **fill level, waste type, and distance from the collection depot**, helping identify bins that require immediate attention.

The project demonstrates how basic Java programming concepts can be applied to solve a practical real-world problem.

##  Objectives

* Monitor waste bins and their fill levels.
* Identify bins requiring urgent collection.
* Prioritise bins using waste type, fill percentage, and distance.
* Reduce unnecessary collection trips.
* Provide a simple and user-friendly waste management system.

##  Key Features

* View all registered waste bins.
* Add new waste bins dynamically.
* Calculate the priority of each bin.
* Identify the highest-priority bin.
* Detect critical bins with fill levels of 80% or above.
* Support different waste types such as Organic, Recyclable, and General.
* Menu-driven and easy-to-use interface.

##  Priority Calculation

The project uses the following priority formula:

**Priority = Fill Percentage + Waste Type Urgency − Distance**

Waste type urgency:

| Waste Type | Urgency |
| ---------- | ------: |
| Organic    |      30 |
| Recyclable |      20 |
| General    |      10 |

A higher priority score indicates that the bin should receive greater attention.

##  Technologies Used

* **Java**
* Object-Oriented Programming
* Classes and Objects
* Methods
* ArrayList
* Conditional Statements
* Loops
* Switch-Case
* Strings
* Exception/validation concepts
* Decision-making logic

##  Project Structure

```text
Municipal-Waste-Collection-Optimiser/
│
├── MunicipalWasteOptimizer.java
├── README.md
└── Project-Report.pdf
```

## How to Run

### 1. Install Java

Make sure Java JDK is installed on your computer.

Check the installation using:

```bash
java -version
```

### 2. Compile the program

Open the terminal in the project folder and run:

```bash
javac MunicipalWasteOptimizer.java
```

### 3. Run the program

```bash
java MunicipalWasteOptimizer
```

##  Menu Options

```text
1. Display all bins
2. Find priority bin
3. Add new bin
4. Show critical bins
5. Exit
```

##  Advantages

* Helps organise waste collection.
* Can reduce unnecessary collection trips.
* Helps prevent overflowing bins.
* Saves time and collection resources.
* Provides priority-based decision making.
* Simple and cost-effective implementation.
* Can be expanded for larger municipal systems.

##  Future Enhancements

The project can be further developed by adding:

* **IoT sensors** for real-time bin-level monitoring.
* **GPS integration** for tracking collection vehicles.
* **Route optimisation** for efficient vehicle movement.
* **Database integration** for storing collection records.
* **Mobile application** for municipal workers.
* **Real-time notifications** when bins reach critical levels.
* **AI and machine learning** for predicting waste generation.
* Multiple vehicles and collection-route management.

##  Learning Outcomes

This project provides practical experience in:

* Applying Java programming to a real-world problem.
* Understanding Object-Oriented Programming.
* Working with collections such as `ArrayList`.
* Using methods and decision-making structures.
* Designing menu-driven applications.
* Developing logical priority-based solutions.

##  Conclusion

The **Municipal Waste Collection Optimiser** demonstrates how a simple Java application can support more organised and efficient waste management. By prioritising bins according to important factors such as fill level, waste type, and distance, the system provides a foundation for developing smarter municipal waste collection solutions.

##  Project

**Language:** Java
**Project Type:** BTech Academic Project
**Domain:** Smart Waste Management
 
