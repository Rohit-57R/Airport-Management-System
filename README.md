# ✈️ Airport Management System (Oracle SQL)

A fully structured **Airport Management System** built using **Oracle SQL**, designed to manage flight operations, passenger records, bookings, crew assignments, and airport logistics efficiently.

---

## 🚀 Project Overview

This project simulates real-world airport operations using a **relational database system**.
It focuses on **data organization, query optimization, and business-level insights** through SQL.

---

## 🛠️ Technologies Used

* **Oracle SQL**
* DDL (Data Definition Language)
* DML (Data Manipulation Language)
* Joins & Subqueries
* Aggregation & Analytical Queries

---

## 📂 Project Structure

```
Airport-Management-System/
│── schema.sql      → Table creation (Database design)
│── data.sql        → Sample data insertion
│── queries.sql     → Queries (basic + advanced)
│── README.md       → Project documentation
```

---

## 🧠 Database Design

The system includes multiple interconnected tables:

* Airports
* Airlines
* Aircraft
* Flights
* Flight Schedule
* Daily Flight Status
* Passengers
* Booking
* Tickets
* Crew & Crew Assignments
* Gates & Boarding Passes
* Baggage
* Maintenance Log

👉 Designed using **normalized relational schema** to reduce redundancy and improve consistency.

---

## 🔗 Key Relationships

* Airports linked with Flights (Origin & Destination)
* Flights connected to Airlines & Aircraft
* Flight Schedule → Daily Flight Status
* Booking → Tickets → Passengers
* Crew assigned to flights
* Boarding, baggage, and maintenance tracking

---

## 📊 Key Functionalities

* Retrieve passenger travel details
* Track flight schedules and statuses
* Manage bookings and ticket information
* Monitor baggage and boarding details
* Assign crew to flights
* Maintain aircraft logs

---

## 📈 Advanced Query Highlights

* Complex **nested subqueries**
* Optimized **JOIN queries**
* Aggregation using `COUNT`, `SUM`
* Business insights such as:

  * Total revenue from bookings
  * Most active airport
  * Airline with maximum flights
  * Delayed flight tracking
  * Passenger activity analysis

---

## ▶️ How to Run

1. Open Oracle SQL environment (SQL*Plus / SQL Developer)
2. Run the files in order:

```
schema.sql
data.sql
queries.sql
```

---

## 💡 Sample Use Cases

* Find destination airport of a passenger
* Retrieve passengers landing at a specific city
* Identify highest capacity aircraft
* Track delayed or cancelled flights
* Analyze airline performance

---

## ⚡ Performance Optimization

* Used **normalized schema design**
* Applied **efficient JOIN queries**
* Implemented **aggregation for faster insights**
* Reduced redundancy and improved consistency

---


## ⭐ Key Takeaway

This project demonstrates strong knowledge of:

* Relational Database Design
* SQL Query Optimization
* Complex Query Writing
* Real-world System Modeling


