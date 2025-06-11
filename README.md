# Calculator CLI Project

## Overview

This is a command-line calculator application built in Python.  
It allows the user to perform basic arithmetic operations via a REPL (Read-Eval-Print Loop) interface.

Supported operations:

- add
- subtract
- multiply
- divide (with division by zero handling)

## Setup Instructions

### 1️⃣ Create and activate virtual environment

```bash
python3 -m venv venv
source venv/bin/activate
```

### 2️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

### Running the Calculator

```bash
python main.py
```

### Running Tests

```bash
pytest --cov=app --cov-report=term
```

### GitHub Actions CI

- GitHub Actions is configured to run tests and enforce **100% test coverage** on every push.
