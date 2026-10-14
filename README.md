# PassForge

### A Java-Based Password Generator

PassForge is a Java application designed to generate passwords using character sets. It demonstrates core Java programming concepts through a modular and practical application.

## Features

- **Password Generation:** Generate passwords through a Java application.
- **Character Set Handling:** Organize the characters used in password construction.
- **Modular Design:** Separate functionality across dedicated Java classes.
- **Object-Oriented Programming:** Apply Java classes, methods, and reusable logic.

## Technology Stack

- Java
- Java Development Kit (JDK)

## Project Structure

```text
PassForge/
├── README.md
└── PassForge/
    └── src/
        ├── Alphabet.java
        ├── Generator.java
        ├── GeneratorTest.java
        ├── Main.java
        └── Password.java
```

## Getting Started

Install a Java Development Kit (JDK) and verify the installation:

```bash
java -version
javac -version
```

### Clone the Repository

```bash
git clone https://github.com/sangushetty1129-art/PassForge.git
cd PassForge/PassForge
```

### Compile and Run

```bash
javac -d out src/Alphabet.java src/Generator.java src/Password.java src/Main.java
java -cp out Main
```

These commands assume the Java classes have no package declarations and `Main.java` is the entry point.

## Future Improvements

- Customizable password length
- Character selection options
- Secure random number generation
- Password strength evaluation

## Developer

**Sangamesh S S**

[GitHub Profile](https://github.com/sangushetty1129-art)
