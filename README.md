Java Login & OTP Authentication System – Project Report

Developer: Mohammed Arsalan Ahmed
Language: Java

1. Project Overview

This project implements a console-based login and registration system in Java with OTP-based authentication. It simulates a basic user authentication workflow, including sign-up, login, email verification, and password validation. The system is designed for educational purposes to demonstrate object-oriented programming, input validation, and secure user verification logic.

2. Objective

Create a user-friendly authentication system.

Implement sign-up and login functionality with OTP verification.

Validate user input for username, email, and password.

Handle incorrect inputs through loops and conditional checks.

Gain practical experience in Java programming, random number generation, and control structures.

3. Features

Sign-Up

Users can register with a username, Gmail, and password.

A 4-digit OTP is generated randomly and displayed.

Users must confirm the OTP to complete registration.

Login

Users can log in using the previously registered username, Gmail, and password.

Input validation ensures that Gmail contains “@” and matches the registered email.

Password verification ensures correct authentication before access.

Input Validation & Error Handling

Loops handle incorrect username, Gmail, or password entries.

OTP re-entry is enforced until correct input is provided.

Exit Option

Users can safely exit the system with confirmation messages.

4. Tools & Techniques Used

Java Scanner class: For user input

Random class: To generate OTPs

Control structures: if-else, switch-case, do-while loops

String methods: Validation of email and password

5. Methodology

The program prompts the user to Sign-Up, Login, or Exit.

During sign-up, it collects username, Gmail, and password, generates an OTP, and validates it.

During login, it verifies username, Gmail, and password through nested validation loops.

Feedback is provided for invalid inputs, ensuring secure and correct user authentication.

The program continues until the user selects Exit.

6. Skills Demonstrated

Java programming fundamentals

User input handling and validation

Random number generation and OTP logic

Control flow and error handling

Basic console-based user authentication design

7. Outcome

Upon completion, this project demonstrates the ability to:

Develop a basic but functional authentication system in Java

Implement OTP verification and input validation

Write clean and structured control logic for real-world scenarios

8. Future Enhancements

Integrate with GUI for a better user interface

Store credentials securely using encryption or hashing

Connect to a database for persistent storage

Implement email/SMS OTP delivery instead of console output.
