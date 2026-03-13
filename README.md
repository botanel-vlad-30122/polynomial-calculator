# Polynomial Calculator ✨

A Java desktop application for performing mathematical operations on polynomials, built with a graphical user interface and structured using the MVC design pattern.

---

## Overview 📝

This application allows users to input two polynomials and perform a variety of operations on them through an intuitive GUI. The project was built as part of an Object-Oriented Programming course, with a focus on clean architecture, separation of concerns, and robust input handling.

---

## Features 🌟

| Operation | Description |
|---|---|
| ➕ Addition | Computes the sum of two polynomials |
| ➖ Subtraction | Computes the difference between two polynomials |
| ✖️ Multiplication | Multiplies two polynomials together |
| ➗ Division | Returns both the quotient and remainder |
| 📈 Derivation | Computes the derivative of a polynomial |
| ∫ Integration | Computes the indefinite integral of a polynomial |

---

## Architecture 🏗️

The application follows the **MVC (Model-View-Controller)** design pattern:

```
src/
├── model/
│   └── Polynomial.java        # Polynomial representation and math logic
├── view/
│   └── CalculatorView.java    # Java Swing GUI
└── controller/
    └── CalculatorController.java  # Connects view and model
```

- **Model** — Represents polynomials as maps of degree → coefficient. Implements all mathematical operations.
- **View** — Built with Java Swing. Handles user input and displays results.
- **Controller** — Processes user actions from the view and delegates to the model.

---

## Technologies 💻

- **Java 8+** — Core language
- **Java Swing** — GUI framework
- **MVC Design Pattern** — Architectural pattern for separation of concerns
- **Maven** — Project build tool

---

## Getting Started 🚀

### Prerequisites
- Java 8+
- IDE (IntelliJ IDEA, Eclipse, or VS Code with Java support)
- Maven (optional, for build management)

### Installation & Running

Clone the repository:
```sh
git clone https://github.com/botanel-vlad-30122/polynomial-calculator.git
```

Open the project in your preferred IDE and run `Main.java` to start the application.

---

## Usage 🛠️

1. Input two polynomials in the provided text fields using the format: `3x^3 + 2x^2 - x + 5`
2. Select the desired operation by clicking the corresponding button
3. The result is displayed in the output area

### Example

**Input:**
```
P(x) = 3x^3 + 2x^2 - x + 5
Q(x) = x^2 - 4x + 7
```

**Addition result:**
```
R(x) = 3x^3 + 3x^2 - 5x + 12
```

**Division result:**
```
Quotient:  3x + 2
Remainder: 13x - 9
```

---

## Key Implementation Details 🔍

- Polynomials are internally represented as `HashMap<Integer, Double>` where the key is the degree and the value is the coefficient — allowing efficient access and manipulation of terms
- The division algorithm implements polynomial long division, returning both quotient and remainder
- Input parsing handles edge cases such as missing coefficients, negative terms, and constant polynomials
- The MVC structure ensures the mathematical logic is fully independent from the UI, making the codebase easy to extend or test

---

## Future Improvements 🚧

- Support for fractional and complex coefficients
- Graphical plotting of polynomials
- Export results as text or PDF
- Unit tests for all mathematical operations

---

## License 📄

This project was developed for educational purposes as part of an Object-Oriented Programming course at the Technical University of Cluj-Napoca."# polynomial-calculator" 
"# polynomial-calculator" 
"# polynomial-calculator" 
"# polynomial-calculator" 
