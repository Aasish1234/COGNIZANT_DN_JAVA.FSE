# Singleton Logger Patterns in Java

This project demonstrates five different implementations of the Singleton Design Pattern using simple logger classes.

## Overview

Each logger class uses a different method to ensure that only one instance of the logger is created. The `Main` class prompts user input and logs messages using each singleton pattern.

---

## Logger Implementations

| Logger Type | Class Name | Description |
| :--- | :--- | :--- |
| Eager Initialization | `EagerLogger` | Instance created at class loading time |
| Lazy Initialization | `LazyLogger` | Instance created only when first requested |
| Double-Checked Locking | `DoubleCheckedLogger` | Thread-safe lazy initialization using a synchronized block |
| Inner Static Class | `InnerClassLogger` | Thread-safe lazy initialization using a static holder class |
| Enum Singleton | `EnumLogger` | Inherently thread-safe and proof against reflection/serialization issues |

---

## Project Structure

* `Main.java` - Handles user input and executes each logger.
* `EagerLogger.java`
* `LazyLogger.java`
* `DoubleCheckedLogger.java`
* `InnerClassLogger.java`
* `EnumLogger.java`

---

## How to Run

1. **Compile all Java files:**
   ```bash
   javac *.java