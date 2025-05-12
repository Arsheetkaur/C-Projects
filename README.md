# C Projects by Arsheet Kaur

A collection of beginner-friendly C projects to improve programming skills. Each project includes a short description and a screenshot of the output.

---

## Project 1: Number Guessing Game

A simple number guessing game where the user tries to guess a randomly generated number between 1 and 100.

### Features:
- Takes user input
- Gives hints (Too high / Too low)
- Displays number of attempts
- Simple terminal-based interface


![image](https://github.com/user-attachments/assets/09647e77-8198-4230-add2-5b8a9b6c8c62)


# Project 2: Simple Calculator in C

---

This is a simple command-line calculator written in C. It allows the user to perform basic mathematical operations including addition, subtraction, multiplication, division, modulus, and exponentiation (power). The program runs in a loop until the user chooses to exit.

# Features:
- Addition
- Subtraction
- Multiplication
- Division (with zero-check)
- Modulus (with zero-check, using integers)
- Power (using math.h library)
- Input validation for menu choices
- Graceful error handling using stderr
  
![image](https://github.com/user-attachments/assets/b8d5cb8d-5a32-4901-9b10-e4f5062fcaca)


## Project 3 - Terminal-Based Digital Clock

This project is a terminal-based digital clock written in C. It displays the current *time and date, updating every second. The user can choose between **12-hour* and *24-hour* time formats.

### Features

- Live digital clock updates every second
- Displays full current date (e.g., Thursday May 08 2025)
- Supports both 12-hour and 24-hour formats
- Cross-platform screen clearing (Windows and Unix-based)
- Simple terminal interface

### How It Works

- The user is prompted at launch to select a time format.
- The program enters an infinite loop, updating time and date every second.
- The screen is cleared and updated each second to simulate a digital clock.


![image](https://github.com/user-attachments/assets/180c3560-5768-4eb3-8981-1d093d7c51c4)


# Project 4: Multi-Task Progress Bar Simulation

This project is a simple C program that simulates multiple tasks progressing in real-time using terminal-based progress bars. It visually displays how each task advances over time with a random step increment.

## Features

- Simulates up to 10 tasks running simultaneously.
- Each task progresses from 0% to 100% with a randomly assigned speed.
- Terminal-based dynamic progress bars.
- Automatically clears and updates the screen each second to animate progress.
- Lightweight and runs in any standard terminal environment.

## How it Works

- Each task is represented using a struct with an ID, progress percentage, and a step size.
- On each loop iteration, tasks advance by their step size until reaching 100%.
- The screen is cleared and re-rendered every second using ANSI terminal control for smooth animation.

![image](https://github.com/user-attachments/assets/17cbc971-c93b-4f4b-b000-dc1304fd7b69)


## Project 4 - User Management System in C

This project is a simple *User Management System written in C. It allows users to register and log in, with their credentials stored in memory. Password input is **masked* for privacy during entry.

## Features

- Register new users (up to 10)
- Secure login with password masking
- In-memory credential handling using structs
- Console-based interface

## Technologies Used

- C Language
- Console I/O with stdio.h and conio.h
- Password masking using _getch() (Windows-compatible)

## How It Works

1. On running the program, you'll get options to:
   - Register a new user
   - Login with credentials
   - Exit the application
2. During password entry, characters are hidden behind *.
3. Username and password are checked against stored users in memory.

## Requirements

- Windows OS (uses <conio.h>)
- GCC or any standard C compiler

![image](https://github.com/user-attachments/assets/b1426096-843b-4d16-8c7c-692fa7f77241)




