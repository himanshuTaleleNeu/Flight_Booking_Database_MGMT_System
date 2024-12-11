# ✈️ Flight Booking System

The Flight Booking System is a comprehensive project designed to automate and streamline the process of flight reservations. It efficiently manages flight data, passenger details, travel classes, payments, and services through a centralized database system. By leveraging detailed ER diagrams and insightful data visualizations, the system offers a robust solution for airlines to enhance their operations, minimize redundancy, and improve user experiences.

---

##  🌟 Overview

The Flight Booking System simplifies the complexities of managing flight data and booking operations. By integrating advanced database design and data visualization, the system ensures smooth operations for airlines while providing users with an easy-to-navigate booking process.

---

## 🚀 Features

- Centralized database to manage passenger, flight, and booking information.
- Automated tracking of seat availability, reservations, and payments.
- Robust data visualization for actionable insights into travel class preferences, busiest airports, and revenue generation.
- Enhanced data integrity, reducing redundancy and ensuring consistent updates.
- Secure access for authorized users to prevent unauthorized data manipulation.

---

## 🎯 Objectives

1. Efficiently track and maintain flight booking records.
2. Minimize errors through automation and centralized data management.
3. Provide detailed insights into revenue, travel classes, and airport activity.
4. Streamline the payment process while ensuring payment status tracking.
5. Enable users to retrieve flight schedules, check reservations, and access ticket cost details.

---

## 🛠️ System Design

The system leverages an **Entity-Relationship (ER) Diagram** to define relationships between entities such as Passengers, Flights, Reservations, Payment Status, and Services.

### 🗺️ ER Diagram
<img src="./images/Flight Booking System.jpg" alt="ER_Diagram" width="800"/>

### Key Entities
- **Airport**: Stores airport details, including location and associations with flights.
- **Passenger**: Manages user details and reservations.
- **Flight Details**: Captures flight schedules, source, destination, and travel class details.
- **Reservation**: Links passengers, seats, and payments.
- **Payment Status**: Tracks payment progress and status for each reservation.

---

## 💾 SQL Implementation

### **Details of SQL Files:**
1. **Encryption.sql**:
   - Includes SQL commands to implement encryption for sensitive data, such as passenger details and payment information.
   
2. **P4_FBS_DDL.sql**:
   - Contains Data Definition Language (DDL) commands for creating tables, defining schemas, and setting up relationships.

3. **P4_FBS_DML.sql**:
   - Provides Data Manipulation Language (DML) scripts for inserting, updating, and deleting records in the database.

4. **Procedures.sql**:
   - Includes stored procedures to handle operations such as retrieving passenger details, flight availability, and cost calculations.

5. **Procedure Executes.sql**:
   - Demonstrates the execution of stored procedures with test cases.

6. **Triggers and UDF.sql**:
   - Defines triggers for maintaining data integrity and User Defined Functions (UDFs) for reusable database logic.

7. **view.sql**:
   - Contains SQL statements for creating views to simplify complex queries.

8. **Views_Check.sql**:
   - Validates the views to ensure accurate data retrieval.

---

## 📊 Data Insights

### 1. **Busiest Airports by City**
<img src="./images/Busiest Aiport by City.png" alt="Busiest Airports by City" width="800"/>

### 2. **Opted Travel Classes**
<img src="./images/Opted Travel Classes.png" alt="Opted Travel Classes" width="800"/>

### 3. **Revenue by Class**
<img src="./images/Revenue by Class.png" alt="Revenue by Class" width="800"/>

These visualizations provide actionable insights into passenger preferences, travel class usage, and revenue contribution.

---

## 🏁 Conclusion

The Flight Booking System showcases a comprehensive approach to managing and analyzing flight reservation data. By integrating database management, automation, and data visualization, the project demonstrates how technology can streamline operations and deliver actionable insights. The system not only simplifies airline operations but also enhances the user experience, making it a valuable solution for the aviation industry.

---