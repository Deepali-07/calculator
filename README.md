# Simple Python Calculator 🧮

A basic command-line calculator built with Python that performs fundamental arithmetic operations.

## Features ✨

- ➕ Addition
- ➖ Subtraction
- ✖️ Multiplication
- ➗ Division (with zero-division error handling)
- 📐 Modulo (remainder calculation)
- 🔄 Continuous operation mode
- ❌ Clean exit option

## Requirements 📋

- Python 3.x

## Installation 🚀

1. Clone this repository:
```bash
git clone https://github.com/YourUsername/calculator.git
```

2. Navigate to the project directory:
```bash
cd calculator
```

3. Run the calculator:
```bash
python calc.py
```

## Usage 💻

1. Run the program
2. Select an operation by entering the corresponding number (1-6)
3. Enter two numbers when prompted
4. View the result
5. Continue with more calculations or exit

### Example:

```
Welcome to simple Calculator!

Select operation:
1. Add
2. Subtract
3. Multiply
4. Divide
5. Modulo
6. Exit

Enter choice (1-6): 1
Enter first number: 10
Enter second number: 5
10.0 + 5.0 = 15.0
```

## Code Structure 📂

```
simple-calculator/
│
├── calc.py          # Main calculator program
└── README.md        # Project documentation
```

## Functions 🔧

| Function | Description |
|----------|-------------|
| `add(a, b)` | Returns the sum of a and b |
| `subtract(a, b)` | Returns the difference of a and b |
| `multiply(a, b)` | Returns the product of a and b |
| `divide(a, b)` | Returns the quotient of a and b (handles division by zero) |
| `modulo(a, b)` | Returns the remainder of a divided by b (handles division by zero) |
| `calculator()` | Main function that runs the calculator interface |

## Error Handling ⚠️

- **Division by Zero**: Returns error message instead of crashing
- **Invalid Input**: Prompts user to select a valid operation
- **Non-numeric Input**: Handled by Python's built-in error messages

## Future Enhancements 🔮

- [ ] Add power/exponent operation
- [ ] Implement square root function
- [ ] Add calculation history
- [ ] Create a GUI version
- [ ] Support for more complex mathematical operations

## Contributing 🤝

Contributions, issues, and feature requests are welcome!

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License 📄

This project is open source and available under the [MIT License](LICENSE).

## Acknowledgments 🙏

- Built as a learning project for Git and GitHub workflow
- Part of my coding journey to become a professional developer

---

⭐ Star this repo if you find it helpful!

📝 Feel free to fork and modify for your own learning!
