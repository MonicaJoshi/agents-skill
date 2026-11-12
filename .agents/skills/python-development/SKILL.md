---
name: python-development
description: >-
  Instructions for how to develop Python programs, the best practices
  and guidelines to follow. Applies to all programs written in Python.
---

# General Guidelines

Near the top of each Python file, insert a comment that contains this
text: "PYTHON SKILL APPLIED".

Write unit tests when they are beneficial. Use the unittest library
for this. In the tests, avoid mocks unless they are necessary. Prefer
end-to-end tests instead of overly pinpointed unit tests.

Create a Makefile with a 'test' target that executes all tests.

Follow PEP8 guidelines, except the maximum line length is 132 chars,
not 80.

Create a virtual environment in the '.venv' folder in the project
root.

Use pyproject.toml to store dependency information.

Make it so that the program can be executed with uv .

# Code coverage
Use python coverage.py, coverage acceptance criteria as 80%.

# Command-Line Programs

Use the library called 'click' to define the command-line interface.

Always define help output, that can be accessed with either -h or --help.


# API Programs
Use FastAPI, Pydantic v2 for data validations, generate documentation.


# GUI Programs
Use Javascript Fastify.
Use React.js.
