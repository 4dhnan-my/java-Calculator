# Java Swing Calculator

A desktop calculator built with Java Swing. The source creates a calculator window with number buttons, decimal input, arithmetic operators, an equals button and an all-clear control.

## Tech stack

- Java
- Java Swing (AWT/Swing event handling and UI components)

## Requirements

- JDK installed
- `javac` and `java` available on your PATH

## Run locally

The repository currently stores the Java source as an extensionless file named `java-calculator`, although its public class is named `Calculator`. Copy it to the matching Java source filename before compiling.

**Windows PowerShell**

```powershell
Copy-Item java-calculator Calculator.java
javac Calculator.java
java Calculator
```

**macOS/Linux**

```bash
cp java-calculator Calculator.java
javac Calculator.java
java Calculator
```

A desktop environment is required to display the Swing window.

## Project note

This is a basic desktop calculator practice project. The source is kept unchanged; the copy step is only to satisfy Java's public-class filename requirement.
