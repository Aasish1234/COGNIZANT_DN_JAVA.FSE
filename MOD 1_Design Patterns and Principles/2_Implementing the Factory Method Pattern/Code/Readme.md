# Implementing the Factory Method Pattern in Java

This project demonstrates the Factory Method Design Pattern by implementing a flexible system to generate different document types dynamically.

## Overview

The Factory Method pattern defines an interface for creating an object but lets subclasses decide which class to instantiate. This project showcases this by creating specialized factories for Word, PDF, and Excel documents.

---

## Factory Implementations

| Component | Class / Interface Name | Description |
| :--- | :--- | :--- |
| Core Product | `Document` | Abstract class or interface defining the product |
| Concrete Products | `WordDocument`, `PdfDocument`, `ExcelDocument` | Specific document types implementing the core product |
| Core Creator | `DocumentFactory` | Abstract class or interface declaring the factory method |
| Concrete Creators | `WordFactory`, `PdfFactory`, `ExcelFactory` | Specific factory classes that override the factory method to return concrete documents |
| Simple Factory | `SimpleDocumentFactory` | A conditional-based factory alternative |
| Configuration | `DocumentType` | Enum representing the supported document types |

---

## Project Structure

Based on the source directory, the files are organized as follows:

* `Main.java` - The entry point that runs and tests the factory implementations.
* `Document.java`
* `DocumentFactory.java`
* `DocumentType.java`
* `ExcelDocument.java`
* `ExcelFactory.java`
* `PdfDocument.java`
* `PdfFactory.java`
* `SimpleDocumentFactory.java`
* `WordDocument.java`
* `WordFactory.java`

---

## How to Run
  
1. **Navigate to the code directory and compile all Java files:**
   ```bash
   javac *.java
2. **Run the Main File:**
   ```bash
   java Main 
