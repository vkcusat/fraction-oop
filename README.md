# Custom Fraction Data Type in Python

A custom Python implementation of a Fraction data type built inside a Jupyter Notebook. This project demonstrates foundational concepts of **Object-Oriented Programming (OOP)** and **Operator Overloading** in Python.

## 🚀 Features
- Custom initialization of numerator and denominator values.
- Dunder method overrides (`__str__`) for clean string representation.
- Operator overloading for standard mathematical operations:
  - Addition (`+`)
  - Subtraction (`-`)
  - Multiplication (`*`)
  - Division (`/`)

## 📂 Repository Structure
- `fraction_data_type.ipynb`: The primary Jupyter Notebook containing the `Fraction` class implementation and test outputs.
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

## 🛠️ Requirements
To run this project locally, you will need:
- Python 3.x
- Jupyter Notebook or JupyterLab
