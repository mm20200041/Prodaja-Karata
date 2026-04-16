# Sports Event Ticket Sales and Validation System 🎟️


This project is a Java client-server system for selling and validating tickets for sports events. The system simulates a real ticket sales process, ticket generation, and QR code-based validation. The application is divided into multiple components to achieve better organization and separation of concerns.
<br>&nbsp;

## 🧩 Project Structure

This repository serves as the central documentation and overview of the entire system. The project consists of the following parts:
<br>&nbsp;

🔹 Client Application

A desktop application (Swing) for operators — managing events and selling tickets.

👉 https://github.com/mm20200041/Prodaja-Karata-Klijent
<br>&nbsp;

🔹 Server Application

Handles business logic, database operations, and client communication.

👉 https://github.com/mm20200041/Prodaja-Karata-Server
<br>&nbsp;

🔹 Shared Module

Contains shared classes (models, communication objects, utility classes) used by both client and server.

👉 https://github.com/mm20200041/Prodaja-Karata-Zajednicki
<br>&nbsp;

## 🚀 Features

-Match, hall, sector, row, and seat management

-Automated ticket generation for each match

-Invoice creation with multiple ticket items

-PDF ticket generation with embedded QR codes

-Email delivery of tickets to customers

-QR code-based ticket validation

-Prevention of duplicate ticket usage
<br>&nbsp;

## 🛠 Technologies

-Java, Swing (GUI), JDBC, MySQL

-HTTP (client-server communication)

-PDF generation, QR code processing
<br>&nbsp;

## 🧱 Architecture

-Client handles user interaction (GUI)

-Server processes business logic and database operations

-Shared module enables data exchange between components

-Validation prevents ticket misuse
<br>&nbsp;

## 🔮 Possible Improvements

-REST API instead of current communication protocol

-Web application instead of desktop (Swing) solution

-Payment system integration

-Mobile application for ticket scanning

-User authentication and role management
