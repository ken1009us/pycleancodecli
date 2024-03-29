# Python Comment-out Code Cleaner CLI

[![PyPI version](https://badge.fury.io/py/pycleancodecli.svg)](https://badge.fury.io/py/pycleancodecli)

Python Code Cleaner CLI ([pycleancodecli](https://github.com/ken1009us/pycleancodecli)) is a tool designed to clean up Python files by removing comments and unnecessary whitespace. It helps in maintaining a cleaner, more readable codebase.

## Prerequisites

- Python 3.6 or higher

## Installation

1. Install directly from PyPI:

```bash
pip install pycleancodecli
```

## Usage
To use pycleancodecli, run the following command in your terminal:

```bash
pycleancodecli FILE_PATHS [OPTIONS]
```

Options:

--dry-run: Display the changes without applying them.

Example:

```bash
pycleancodecli example.py --dry-run
```

This will clean up example.py and show the cleaned code without overwriting the original file.

## Project Structure

- pycleancodecli\: Main project folder.
    - cleaner: Contains the core cleaning functionality.
- tests\: Contains test cases for the tool.
    - test_cleaner.py: Test script for the cleaner module.
- setup.py: Setup script for packaging and distribution.

## Improvements

Future improvements and features can include:

- Enhanced comment detection and removal logic.
- Options for different cleaning levels based on user preference.

Feel free to contribute to the project by submitting pull requests or opening issues for bugs and feature requests on GitHub.