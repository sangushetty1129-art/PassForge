# Password Generator

A Java console application that generates random passwords based on user-selected character types and evaluates password strength using multiple security criteria.

---

## Overview

The Password Generator is a Java-based console application designed to help users create stronger passwords and understand the basic characteristics of password security.

The application provides three main functionalities:

* Random password generation
* Password strength checking
* Password security information

The project was developed to practice Java programming, object-oriented programming concepts, user input handling, string manipulation, randomization, and basic password-security logic.

---

## Features

### 1. Random Password Generation

The application allows users to customize the type of characters included in the generated password.

The user can choose whether to include:

* Uppercase letters
* Lowercase letters
* Numbers
* Symbols

The user then specifies the desired password length.

Based on these choices, the application creates a character set and randomly selects characters to generate the password.

### 2. Password Strength Checker

The application evaluates a password using multiple criteria.

The following factors are checked:

* Use of uppercase letters
* Use of lowercase letters
* Use of numbers
* Use of symbols
* Password length of 8 or more characters
* Password length of 16 or more characters

A score is calculated based on the satisfied criteria, and the application displays an overall strength level such as:

```text
Weak
Medium
Good
Great
```

### 3. Password Security Information

The application also provides useful information about creating safer passwords.

It highlights practices such as:

* Avoiding reuse of the same password
* Avoiding excessive character repetition
* Avoiding keyboard patterns
* Avoiding common dictionary words
* Avoiding predictable letter or number sequences

---

## How It Works

The application follows a simple console-based workflow:

```text
Start
  ↓
Choose Password Character Types
  ↓
Enter Password Length
  ↓
Generate Character Set
  ↓
Generate Random Password
  ↓
Display Password
  ↓
Check Password Strength
  ↓
Display Strength
  ↓
Show Password Security Information
```

---

## Technology Used

| Technology                  | Purpose                                  |
| --------------------------- | ---------------------------------------- |
| Java                        | Core programming language                |
| Object-Oriented Programming | Application structure and implementation |
| Java Randomization          | Random password generation               |
| String Handling             | Password and character processing        |
| Console Input/Output        | User interaction                         |

---

## Project Structure

```text
Password-Generator/
│
├── src/
│   ├── Alphabet.java
│   ├── Generator.java
│   ├── GeneratorTest.java
│   ├── Main.java
│   └── Password.java
│
└── README.md
```

### Main Components

**Main.java**

Handles the main program flow and user interaction.

**Generator.java**

Handles password generation logic.

**Alphabet.java**

Manages the character sets used for password generation.

**Password.java**

Handles password-related operations, including password strength evaluation.

**GeneratorTest.java**

Contains test code for the password generator functionality.

---

## Requirements

Before running the application, make sure Java is installed.

Check the Java version:

```powershell
java -version
```

Check the Java compiler:

```powershell
javac -version
```

The application can be compiled and executed using the standard Java JDK.

---

## Running the Application

### Method 1: Open Terminal in the `src` Folder

Open the following folder:

```text
Password-Generator/src
```

In Windows File Explorer, right-click inside the folder and select:

**Open in Terminal**

The terminal should open directly in the `src` directory.

### Step 1: Compile the Application

Run:

```powershell
javac Alphabet.java Generator.java Password.java Main.java
```

This compiles the main application classes.

### Step 2: Run the Application

After compilation, run:

```powershell
java Main
```

The application will start in the terminal.

### Complete Commands

If you are already inside the `src` folder, simply run:

```powershell
javac Alphabet.java Generator.java Password.java Main.java
java Main
```

### Important Note About `GeneratorTest.java`

The project also contains:

```text
GeneratorTest.java
```

This file contains JUnit test code and requires the JUnit 5 dependency.

Therefore, the simple application can be compiled without the test file using:

```powershell
javac Alphabet.java Generator.java Password.java Main.java
```

If JUnit is configured separately, the test class can also be compiled and executed using the appropriate JUnit setup.

---

## Example Workflow

```text
Include uppercase letters? Yes
Include lowercase letters? Yes
Include numbers? Yes
Include symbols? Yes

Enter password length: 16

Generated Password:
X7@kP2#vL9!mQ4$s

Password Strength:
Great
```

---

## Development Work

The project focuses on implementing a Java-based password generation and evaluation system.

Key development areas include:

* Java programming
* Object-oriented programming
* Console-based user interaction
* Random password generation
* Character-set handling
* String manipulation
* Password strength evaluation
* Conditional logic
* Basic software testing

---

## Project Status

**Working**

The console-based password generator and password strength checker are implemented and can be executed locally using Java.

---

## Future Improvements

* Develop a graphical user interface
* Add password copy-to-clipboard functionality
* Add customizable password generation options
* Improve password-strength analysis
* Add stronger password-generation algorithms
* Add unit-test configuration using a Java build tool
* Improve overall user experience

---

## Author

**Sangamesh S S**

Information Science & Engineering

### GitHub

**sangushetty1129-art**

---

## Disclaimer

This application is intended for educational and demonstration purposes. Password-strength results are based on the criteria implemented in the application and should not be considered a complete security assessment.
