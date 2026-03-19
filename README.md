# Prodaja-Karata


Project: Ticket Sales and Validation System for Sports Events

Description
This project is a Java client–server application designed for selling and validating tickets for sports events. The system allows management of matches, venues, sectors, rows, and seats, as well as generation and validation of digital tickets.

The application simulates a real ticketing system where tickets are generated for each match, sold to customers, and validated at the entrance using QR codes.

Main Features

Management of sports events, venues, sectors, rows, and seats

Automatic generation of tickets for each event in the database

Creation of invoices with multiple ticket items

Generation of PDF tickets with unique QR codes

Email delivery of tickets to customers

HTTP server for QR code validation at entrance

Prevention of duplicate ticket usage (already scanned tickets are rejected)

Technologies Used

Java

Swing (GUI)

JDBC

MySQL database

PDF generation

QR code generation and validation

HTTP server for ticket verification

System Architecture

The system is designed as a client–server application:

Client application
Used by ticket sales operators to manage events and sell tickets through a graphical user interface.

Server
Handles database communication, business logic, ticket generation, and validation.

Validation service
A lightweight HTTP server verifies QR codes during entry and prevents reuse of tickets.

Possible Improvements

REST API instead of custom server communication

Web-based frontend instead of Swing

Integration with payment gateways

Mobile ticket scanning application
