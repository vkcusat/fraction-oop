# Custom Fraction Data Type in Python

A custom Python implementation of a Fraction data type built and executed inside Google Colab. This project demonstrates foundational concepts of **Object-Oriented Programming (OOP)** and **Operator Overloading** in Python.

## 🚀 Features
- Custom initialization of numerator and denominator values.
- Dunder method overrides (`__str__`) for clean string representation.
- Operator overloading for standard mathematical operations:
  - Addition (`+`)
  - Subtraction (`-`)
  - Multiplication (`*`)
  - Division (`/`)

## 📂 Repository Structure
- `fraction_data_type.ipynb`: The primary notebook containing the `Fraction` class implementation and live test outputs.
- `README.md`: Project overview and documentation.

## 💻 Sample Code Usage

```python
obj = Fraction(3, 4)
obj2 = Fraction(1, 2)

print(obj - obj2)  # Output: 2/8
print(obj + obj2)  # Output: 10/8
print(obj * obj2)  # Output: 3/8
print(obj / obj2)  # Output: 6/4
```

## 🛠️ Environment & Requirements
This project was built on **Google Colab**. You do not need to install anything locally to view it. Simply open the `.ipynb` file right here on GitHub, or download it to run in your own Colab environment.
