# CSCI 2001 – Object-Oriented Programming ☕

Assignments from **CSCI 2001 - Object-Oriented Programming** course.  
All projects are written in **Java** and focus on core OOP principles including encapsulation, classes, arrays, and data structures.

---

## 📁 Repository Structure

```
CSCI-2001-Object-Oriented-Programming/
│
├── Assignment1-UnitConversion/
│   └── A1_Conversion.java
│
├── Assignment2-Car/
│   ├── Car.java
│   └── CarAutoTester.java
│
├── Assignment3-ArrayExplorer/
│   └── ArrayExplorer.java
│
├── Assignment4-ArrayListExplorer/
│   └── ArrayListExplorerWithOutCollections.java
│
├── .gitignore
└── README.md
```

---

## 📚 Assignments

### Assignment 1 – Unit Conversion
Converts between different units of measurement.  
**Concepts:** Input/output, arithmetic operations, data types.

---

### Assignment 2 – Car Class
Models a `Car` object with fuel management and driving logic.  
**Concepts:** Encapsulation, constructors, getters/setters, method design.

Key features:
- Default and overloaded constructors
- `drive(double distance)` — calculates fuel consumption, handles running out of gas
- `fillGas(double amount)` — prevents overfilling the tank
- `canDrive(double distance)` — checks if enough fuel exists for a trip
- `CarAutoTester.java` — automated test suite with scoring

---

### Assignment 3 – Array Explorer
A utility class with static methods for analyzing integer arrays **without** using Java's built-in Collections framework.  
**Concepts:** Static methods, arrays, iteration, exception handling.

Methods: `min`, `max`, `sum`, `average`, `count`, `contains`, `index`, `containsDuplicates`, `sumOfEvens`, `getItem`, `toString`

---

### Assignment 4 – ArrayList Explorer (Without Collections)
Same utility methods as Assignment 3, but operating on `ArrayList<Integer>` instead of raw arrays — still without using `Collections` utility methods.  
**Concepts:** ArrayLists, generics, Javadoc.

Methods: `min`, `max`, `sum`, `average`, `count`, `contains`, `index`, `containsDuplicates`, `sumOfEvens`, `getItem`, `toString`

---

## 🛠 How to Run

### Prerequisites
- Java JDK 8 or higher
- Any Java IDE (Eclipse, IntelliJ, VS Code) or command line

### Running from the command line

```bash
# Navigate to the repo root first
cd CSCI-2001-Object-Oriented-Programming

# Assignment 2
javac Assignment2-Car/Car.java Assignment2-Car/CarAutoTester.java
java Assignment2-Car.CarAutoTester

# Assignment 3
javac Assignment3-ArrayExplorer/ArrayExplorer.java
java Assignment3-ArrayExplorer.ArrayExplorer

# Assignment 4
javac Assignment4-ArrayListExplorer/ArrayListExplorerWithOutCollections.java
java Assignment4-ArrayListExplorer.ArrayListExplorerWithOutCollections
```

---

## 🧠 Topics Covered

| Assignment | Topic |
|---|---|
| A1 – Unit Conversion | Data types, arithmetic, I/O |
| A2 – Car Class | Classes, encapsulation, constructors, method design |
| A3 – Array Explorer | Static methods, arrays, exception handling |
| A4 – ArrayList Explorer | ArrayLists, generics, iteration |

---

## 👤 Author

**Chidera Izuora**  
Computer Science Student  
Course: CS2001 – Object-Oriented Programming

- GitHub: [github.com/cizuora](https://github.com/cizuora)
- Email: cizuora@gmail.com
- LinkedIn: [linkedin.com/in/chidera-izuora-233804146](https://www.linkedin.com/in/chidera-izuora-233804146/)
