# Calcutils

A simple math utility package created for educational purposes.

## Installation

Install the package directly from **TestPyPI**:

```bash
pip install --index-url https://test.pypi.org/simple/ --extra-index-url https://pypi.org/simple/ calcutils-gloria-lab
```

## Usage

```python
from calcutils import operations

# Addition
result = operations.add(10, 25)
print(result)  # Output: 35

# Multiplication
result = operations.multiply(4, 5)
print(result)  # Output: 20

# Average
result = operations.average([10, 20, 30, 40])
print(result)  # Output: 25.0
```

## Features

- `add(a, b)`: Returns the sum of two numbers.
- `multiply(a, b)`: Returns the product of two numbers.
- `average(numbers)`: Returns the arithmetic mean of a list of numbers.

## License

MIT License