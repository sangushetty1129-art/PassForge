# PassForge — Java Password Generator

PassForge is a Java-based password generation application designed to generate passwords using configurable character sets. The project demonstrates core Java programming concepts, modular code organization, and password generation logic.

## Overview

Creating strong passwords is an important part of protecting online accounts and digital information. PassForge provides a simple Java application for generating passwords through a programmatic approach.

The project is built using Java and separates its functionality into dedicated classes for password generation, character handling, and application execution.

## Features

- **Password Generation:** Generate passwords using Java.
- **Character Handling:** Organize character sets for password construction.
- **Modular Design:** Separate classes for generation logic and password-related operations.
- **Java Fundamentals:** Demonstrates object-oriented programming and core Java concepts.
- **Test Class:** Includes a `GeneratorTest.java` source file for testing-related functionality.

## Tech Stack

- **Language:** Java
- **Development Environment:** IntelliJ IDEA / Visual Studio Code
- **Version Control:** Git and GitHub

## Project Structure

```text
PassForge/
├── .gitignore
├── README.md
└── Password_Generator/
    ├── .gitignore
    ├── README.md
    └── src/
        ├── Alphabet.java
        ├── Generator.java
        ├── GeneratorTest.java
        ├── Main.java
        └── Password.java
```

## Getting Started

### Prerequisites

- Java Development Kit (JDK)
- A terminal or command prompt
- Visual Studio Code or IntelliJ IDEA

Verify that Java is installed:

```bash
java -version
javac -version
```

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/sangushetty1129-art/PassForge.git
   ```

2. Navigate to the Java project directory:

   ```bash
   cd PassForge/Password_Generator
   ```

### Compile and Run

From the `Password_Generator` directory, compile the application source files:

```bash
javac -d out src/Alphabet.java src/Generator.java src/Password.java src/Main.java
```

Run the application:

```bash
java -cp out Main
```

Follow the prompts displayed by the application.

*Note: These commands assume the source files do not declare a Java package and that `Main.java` is the application entry point.*

## Learning Objectives

This project provides an opportunity to explore:

- Java classes and methods
- Object-oriented programming
- Character and string manipulation
- Application modularity
- Basic software testing
- Git-based version control

## Future Enhancements

Potential improvements include:

- User-configurable password length
- Options for uppercase letters, lowercase letters, numbers, and special characters
- Password strength evaluation
- Secure random number generation
- Automated unit tests
- A graphical user interface

These are potential enhancements and may not all be implemented in the current version.

## Author

**Sangamesh S S**

GitHub: [@sangushetty1129-art](https://github.com/sangushetty1129-art)

---

If you find this project useful, feel free to explore the source code and suggest improvements.
