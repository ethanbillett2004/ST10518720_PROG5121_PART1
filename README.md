# Chat Application Part 3

## Student Information
- Name: Ethan Gareth Billett  
- Student Number: ST10518720  
- Module: PROG5121  

---

## Project Information
- I have created a program using 4 classes including:
  - Main.java  
  - Login.java  
  - Messages.java  
  - MessagesTest.java  
  - LoginTest.java  

---

## Features

### Username Validation
- Must contain an underscore (_)
- Maximum of 5 characters

---

### Password Validation
- Minimum 8 characters
- Must include:
  - At least one uppercase letter
  - At least one number
  - At least one special character

---

### Cellphone Validation
- South African Phone Validation
- Accepts:
  - Local format: 0XXXXXXXXX
  - International format: +27XXXXXXXXX
- Must follow valid SA mobile number patterns

---

### User Registration
- Stores validated first name, last name, username, password, and phone number
- Validates all inputs before registration

---

### Login System
- Verifies entered credentials against stored user data
- Displays login status using returnLoginStatus() method
- Shows welcome message on successful login

---

## Messaging System

### Message Creation
- Each message includes:
  - Auto-generated Message ID
  - Recipient number
  - Message text (maximum 250 characters)
  - Message number (passed from loop index)
  - Message hash

---

### Message Hash Format
