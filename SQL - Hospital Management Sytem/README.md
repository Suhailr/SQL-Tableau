# 🏥 Hospital Management System SQL Project

## 📖 Overview

The **Hospital Management System SQL Project** is a relational database management solution developed using **MySQL** to simplify and optimize the day-to-day operations of a hospital. The project demonstrates how structured healthcare data can be efficiently managed through a well-designed database system.

Hospitals generate and process large amounts of information daily, including patient records, physician schedules, diagnoses, departmental information, and medical procedures. Managing these records manually is time-consuming, error-prone, and inefficient. This project addresses these challenges by implementing a centralized relational database that improves data organization, accessibility, consistency, and operational efficiency.

The system is designed for educational and analytical purposes and serves as a practical example of database normalization, table relationships, SQL querying, and healthcare data management.



## ✨ Features

* Centralized hospital data management
* Efficient storage and retrieval of patient records
* Physician and department management
* Patient diagnosis tracking
* Nurse and staff record management
* Relational database structure with foreign key relationships
* SQL queries for healthcare data analysis
* Easy-to-understand schema for learning and development


## 🛠️ Technologies Used

| Technology | Description                               |
| ---------- | ----------------------------------------- |
| MySQL      | Relational Database Management System     |
| SQL        | Database querying and management language |


## 🗄️ Database Schema

The project contains the following tables:

## 👨‍⚕️ 1. Physician

Stores information about physicians working in the hospital.

### Fields

* Physician ID
* Name
* Position
* Department Association


## 🔗 2. Affiliated With

Maintains relationships between physicians and departments.

### Fields

* Physician ID
* Department ID
* Affiliation Status


## 🏢 3. Department

Contains details about hospital departments.

### Fields

* Department ID
* Department Name
* Head Physician



## 👩‍⚕️ 4. Nurse

Stores nurse-related information.

### Fields

* Nurse ID
* Name
* Position
* Registered Status



## 🧑‍🦽 5. Patient

Stores patient personal and medical details.

### Fields

* Patient ID
* Name
* Address
* Phone Number
* Date of Birth
* Primary Physician



## 🩺 6. Patient Diagnosis

Maintains patient diagnosis records.

### Fields

* Diagnosis ID
* Patient ID
* Physician ID
* Diagnosis Details
* Diagnosis Date



## ⚕️ 7. Procedures

Stores medical procedure information.

### Fields

* Procedure ID
* Procedure Name
* Cost

## 🎯 Objectives

The primary objectives of this project are:

* To demonstrate practical implementation of SQL concepts
* To design a normalized hospital database schema
* To improve healthcare data management efficiency
* To provide analytical insights using SQL queries
* To simplify hospital record maintenance

## 📚 Learning Outcomes

This project helps in understanding:

* Relational database design
* Primary and foreign keys
* Database normalization
* SQL joins and relationships
* CRUD operations
* Healthcare data management systems

## 👨‍💻 Author
Mohamed Suhal Mohamad Haniff | Data Analyst Enthusiast

