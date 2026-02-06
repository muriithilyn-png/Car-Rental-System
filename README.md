[10:41 AM, 2/6/2026] +254 746 096730: import java.io.Console;
import java.util.Arrays;

/**
 * Simple console login program with 3 attempts.
 * Uses java.io.Console for secure password input (no characters shown while typing).
 * This is the recommended way in Java for console password entry.
 * 
 * Note: Showing * for each character while typing (with backspace support) 
 * requires advanced terminal handling and is not possible with pure standard Java.
 * 
 * Correct credentials for demo: 
 * username: admin
 * password: secret123
 */
public class SecureLoginConsole {

    private static final String CORRECT_USERNAME = "admin";
    private static final String CORRECT_PASSWORD = "secret123";
    private static final int MAX_ATTEMPTS = 3;

    public static void main(String[] args) {
        Con…
[11:12 AM, 2/6/2026] +254 746 096730: # Car Rental System - OOP Java Project

## Overview
Console-based *Car Rental Management System* built in Java using core *Object-Oriented Programming* principles:
- *Encapsulation* → private fields + public getters/methods
- *Abstraction* → clear class responsibilities
- *Composition* → Rental contains Car & Customer
- *Single Responsibility* → each class handles one main concern

## Features
- Add & view available cars
- Register customers (auto-generated IDs)
- Rent a car (with days & total cost calculation)
- Return a car
- View active rentals
- Exception handling for invalid operations

## Technologies
- Java (JDK 17+ recommended)
- NetBeans IDE
- JUnit 5 (for unit testing)

## Project Structure
