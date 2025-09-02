[![Python Template for IDS706](https://github.com/lingyuehao/python_template_706/actions/workflows/main.yml/badge.svg)](https://github.com/lingyuehao/python_template_706/actions/workflows/main.yml)

# python_template_706

## Project Description
This project is a simple Python template that demonstrates professional software development practices.

- **hello.py**: Example file from the template. It defines two basic functions:
  - `say_hello(name)` returns a welcome message.
  - `add(a, b)` returns the sum of two numbers.
- **test_hello.py**: Unit tests for `hello.py`.
- **work.py**: It contains functions related to aviation:
  - `knots_to_kmh(knots)` converts speed from knots to km/h.
  - `estimate_flight_time_hours(distance_nm, speed_knots)` estimates flight time given distance and airspeed.
- **test_work.py**: Unit tests for `work.py`, including normal and edge cases.
- **Makefile**: It contains commands for setup, testing, and linting
- **requirements.txt**: Lists dependencies such as `pytest`, `flake8`, and `black`.


## Setup Instructions
1. Clone the repository: https://github.com/lingyuehao/python_template_706.git
2. Install dependencies:
   ```python
   pip install --upgrade pip
   pip install -r requirements.txt
   ```

## Usage Examples
### Example 1: Functions in the 'hello.py' file
```python
from hello import say_hello, add

print(say_hello("Annie"))
# Output: Hello, Annie, welcome to Data Engineering Systems (IDS 706)!

print(add(2, 3))
# Output: 5
```

### Example 2: Functions in the 'work.py' file
```python
from work import knots_to_kmh, estimate_flight_time_hours

# Convert 550 knots to km/h
print(knots_to_kmh(450))
# Output: 1018.6

# Estimate flight time for a 2500 nautical mile trip at 500 knots
print(estimate_flight_time_hours(2500, 500))
# Output: 5.0
```
