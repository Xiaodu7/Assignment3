# Assignment 3 - Interactive Calculator

This project is an interactive command-line calculator written in Python. It demonstrates object-oriented programming, REPL interaction, error handling, automated testing, parameterized testing, test coverage, and continuous integration with GitHub Actions.

## Features

- Addition
- Subtraction
- Multiplication
- Division
- Interactive REPL interface
- Input validation
- Division-by-zero error handling
- Unit testing with pytest
- Parameterized tests
- 100% test coverage
- Automated testing with GitHub Actions

## Project Structure

- `app/operations/` - Contains the `Operations` class and arithmetic methods.
- `app/calculator/` - Contains the interactive calculator REPL.
- `tests/` - Contains unit and parameterized tests.
- `main.py` - Starts the calculator application.

## Setup

Create a virtual environment:

```bash
python3 -m venv venv
```

Activate the virtual environment:

```bash
source venv/bin/activate
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

## Run the Calculator

```bash
python main.py
```

Example:

```text
add 3 4
Result: 7.0
```

Supported operations:

- `add`
- `subtract`
- `multiply`
- `divide`

Type `exit` to quit the calculator.


## Testing

Run all tests with:

```bash
pytest
```

The project includes unit tests and parameterized tests and maintains 100% test coverage.

## Continuous Integration

GitHub Actions automatically runs the test suite when code is pushed to the `main` branch or when a pull request is created.