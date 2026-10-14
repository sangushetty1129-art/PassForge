# PassForge

### Craft Stronger Passwords with Java

PassForge is a Java-based password generator designed to simplify password creation through a structured, modular approach. It uses character sets and dedicated Java classes to handle the password generation process.

The project combines practical Java programming with a useful everyday application, making it a foundation for exploring password generation, string manipulation, and object-oriented design.

## Overview

Creating unique passwords for different accounts is an important security practice. PassForge provides a straightforward way to generate passwords through a Java application while keeping the underlying logic organized and easy to understand.

## Features

- **Password Generation:** Generate passwords through a Java application.
- **Character Set Management:** Organize the characters used to construct passwords.
- **Modular Code Structure:** Separate password-related functionality into dedicated Java classes.
- **Object-Oriented Design:** Apply Java classes, methods, and reusable program logic.
- **Maintainable Structure:** Keep the application's main components organized for future development.

## Built With

- **Java** — Application logic and password generation.
- **JDK** — Compiling and running the application.
- **Git & GitHub** — Version control and project hosting.

## Project Structure

```text
PassForge/
├── README.md
└── PassForge/
    ├── README.md
    └── src/
        ├── Alphabet.java
        ├── Generator.java
        ├── GeneratorTest.java
        ├── Main.java
        └── Password.java
```

### Core Components

| File | Responsibility |
|---|---|
| `Main.java` | Application entry point |
| `Generator.java` | Password generation logic |
| `Alphabet.java` | Character set handling |
| `Password.java` | Password-related functionality |
| `GeneratorTest.java` | Testing-related code |

## Getting Started

### Prerequisites

Install a Java Development Kit (JDK) and verify that Java is available from your terminal.

```bash
java -version
javac -version
```

### 1. Clone the Repository

```bash
git clone https://github.com/sangushetty1129-art/PassForge.git
```

### 2. Navigate to the Project

```bash
cd PassForge/PassForge
```

### 3. Compile the Application

```bash
javac -d out src/Alphabet.java src/Generator.java src/Password.java src/Main.java
```

### 4. Run PassForge

```bash
java -cp out Main
```

These commands assume the source files have no package declarations and `Main.java` is the entry point.

## Future Enhancements

- Custom password length selection
- Options for uppercase letters, lowercase letters, digits, and special characters
- Cryptographically secure random number generation
- Password strength estimation
- Improved input validation and automated testing

These are possible future improvements, not claims about existing functionality.

## About the Developer

**Sangamesh S S**

Information Science and Engineering

[GitHub Profile](https://github.com/sangushetty1129-art)

---

*PassForge — Simple password generation, built with Java.*
