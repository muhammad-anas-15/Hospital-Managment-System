# Hospital Management System (HMS)

## Introduction
The Hospital Management System (HMS) is a C++ project designed to manage the operations of a hospital. It features a user-friendly interface for managing doctors and patients, including their information, reports, and billing. This project demonstrates various Object-Oriented Programming (OOP) concepts, such as inheritance, encapsulation, and polymorphism.

## Features
### Doctor Management:
- Add new doctors.
- Display individual doctor information.
- Display details of all doctors.
- Calculate and display the total number of doctors.
- Calculate doctors' salaries based on the number of patients treated.

### Patient Management:
- Add new patients.
- Display individual patient information.
- Display details of all patients.
- Calculate and display the total number of patients.
- Generate and display patient reports.
- Calculate and generate bills for patients.

## OOP Concepts Used
### 1. Classes and Objects
The project defines two main classes: Doctor and Patient, both inheriting from an abstract base class Person. These classes represent the entities managed by the system.

### 2. Inheritance
The Doctor and Patient classes inherit from the base class Person. This allows for common functionalities to be defined in the base class and specific functionalities to be implemented in the derived classes.

### 3. Encapsulation
Each class encapsulates the data and methods that operate on the data. The data members of the Doctor and Patient classes are accessed and modified through public member functions, ensuring data integrity and security.

### 4. Polymorphism
The base class `Person` defines virtual functions that are overridden in the derived classes `Doctor` and `Patient`. This allows for dynamic binding and polymorphic behavior.

### 5. Friend Functions
Friend functions are used to allow specific non-member functions to access private data members of the class. For example, the `doc_salary` function is a friend of the `Doctor` class and can access its private members.

## Screenshots

### Main Menu
<img src="https://github.com/user-attachments/assets/7997bf78-32a5-4c60-b3da-cb3ad6b6fb77" alt="Main Menu" width="300"/>

### Doctor Management
<img src="https://github.com/user-attachments/assets/3aea0146-d0ce-41e0-a706-9e5e2509cd0c" alt="Doctor Management" width="300"/>

### Patient Management
<img src="https://github.com/user-attachments/assets/60ce2b93-8ec3-4ce7-abfb-79152dca17b3" alt="Patient Management" width="300"/>



# Requirements
 C Compiler(GCC-Linex Operating System)
 Any IDE(VS-Code, Dev-C++, Code-Blocks)
 
## Contact

For any questions or issues, please contact:

- **Name**: Muhammad Anas
- **Email**: muhammadannas.2356@gmail.com
- **GitHub**: (https://github.com/muhammad-anas-15)

