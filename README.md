<p align="center">
  <img src="https://www.especial.gr/wp-content/uploads/2019/03/panepisthmio-dut-attikhs.png" alt="UNIWA" width="150"/>
</p>

<p align="center">
  <strong>UNIVERSITY OF WEST ATTICA</strong><br>
  SCHOOL OF ENGINEERING<br>
  DEPARTMENT OF COMPUTER ENGINEERING AND INFORMATICS
</p>

<p align="center">
  <a href="https://www.uniwa.gr" target="_blank">University of West Attica</a> ·
  <a href="https://ice.uniwa.gr" target="_blank">Department of Computer Engineering and Informatics</a>
</p>

---

<p align="center">
  <strong>Software Engineering</strong>
</p>

<h1 align="center">
  Preze Cinemas Desktop - Phase 2 <br>
  Software Requirements Specification 
</h1>

<p align="center">
  <strong>Vasileios Evangelos Athanasiou</strong><br>
  Student ID: 19390005
</p>

<p align="center">
  <a href="https://github.com/Ath21" target="_blank">GitHub</a> ·
  <a href="https://www.linkedin.com/in/vasilis-athanasiou-7036b53a4/" target="_blank">LinkedIn</a>
</p>

<hr/>

<p align="center">
  <strong>Supervision</strong>
</p>

<p align="center">
  Supervisor: Georgios Prezerakos, Professor
</p>
<p align="center">
  <a href="https://ice.uniwa.gr/en/emd_person/george-prezerakos/" target="_blank">UNIWA Profile</a> ·
  <a href="https://www.linkedin.com/in/georgenprezerakos/" target="_blank">LinkedIn</a>
</p>

</hr>

---

<p align="center">
  Athens, June 2023
</p>

---

<p align="center">
  <img src="https://s7280.pcdn.co/wp-content/uploads/2017/09/srs-software-requirement-specifications-1024x754.jpg.optimal.jpg" width="250"/>
</p>

---

# README

## Preze Cinemas Desktop - Phase 2 Software Requirements Specification

This repository section documents the **second phase** of the _Preze Cinemas Desktop_ project, developed for the **Software Engineering** course.

Phase 2 focuses on defining the **Software Requirements Specification (SRS)** for the cinema reservation management system.

---

## Table of Contents

| Section | Folder/File                                    | Description                                     |
| ------: | ---------------------------------------------- | ----------------------------------------------- |
|       1 | `assign/`                                      | Assignment instructions and supporting material |
|     1.1 | `assign/seng_instructions_2022_23_v2.pdf`      | Assignment instructions (English)               |
|     1.2 | `assign/λμηχ_οδηγίες_2022_23_β2.pdf`           | Assignment instructions (Greek)                 |
|       2 | `docs/`                                        | Software Requirements documentation             |
|     2.1 | `docs/Software-Requirements-Specification.pdf` | Software Requirements Specification (English)   |
|     2.2 | `docs/Προδιαγραφές-Απαιτήσεων-Λογισμικού.pdf`  | Software Requirements Specification (Greek)     |
|       3 | `README.md`                                    | Repository overview and usage instructions      |

---

## 1. Project Overview

The Cinema Ticket Reservation Management System enables customers to browse movies, reserve tickets, and complete secure payments while allowing cinema operators to manage availability and reservations effectively.

The system aims to provide:

- Easy ticket reservation
- Secure transactions
- Efficient seat management
- Reliable data handling

---

## 2. Core Functionalities

### 2.1 User Management

The system supports both:

- New customer registration
- Secure login for returning users

Authentication ensures account protection and correct access control.

### 2.2 Movie Browsing

Customers can:

- Browse available movies
- Choose viewing formats such as **3D** or enhanced audio options.

### 2.3 Reservation Flow

Reservation steps include:

- Selecting showtime
- Choosing cinema room
- Selecting ticket quantity (up to 9 tickets per transaction)

### 2.4 Availability Management

To prevent conflicts:

- Selected seats are temporarily reserved
- Reservations are held for **8 minutes** during checkout

### 2.5 Payment Integration

The system communicates with external **Bank Systems** to:

- Validate payment details
- Confirm account balance
- Approve transactions

### 2.6 Notification System

Customers may register interest in sold-out screenings and receive notifications if seats become available.

---

## 3. System Architecture

### 3.1 Operating Environment

The desktop system interacts with two primary external entities:

- **Customer** – main user of the application
- **Bank System** – verifies payment transactions

---

## 4. Data Management

A relational database stores and manages:

- **Customer Profiles**  
  Personal details and reservation history.

- **Movie Catalog**  
  Movie schedules, rooms, seat availability, and pricing.

- **Transaction Records**  
  Booking and payment logs.

---

## 5. Security & Constraints

### 5.1 Database Security

The database prevents unauthorized modification or deletion of records.

### 5.2 Functional Constraints

- Passwords must include:
  - At least one uppercase letter
  - At least one number
- Required registration and payment fields must be completed before proceeding.

---

## 6. Conclusion

Phase 2 establishes the **functional and technical requirements** of the Preze Cinemas Desktop system, forming the foundation for implementation and future development phases.
