# 0x03. Unittests and Integration Tests

This repository contains solutions for the "Unittests and Integration Tests" project. The project focuses on understanding and implementing unit tests and integration tests in Python.

## Background Context

Unit testing is the process of testing individual functions or methods in isolation to ensure they return expected results for various inputs. Unit tests focus on verifying the logic defined within a function without involving external dependencies. These dependencies are typically mocked to simulate expected behavior without making actual network or database calls.

The goal of a unit test is to answer the question: **If everything defined outside this function works as expected, does this function work as expected?**

Integration tests, on the other hand, are designed to test the interaction between different parts of the code. These tests aim to verify that the entire code path works as intended, from input to output. Integration tests typically mock low-level functions that make external calls such as HTTP requests, file I/O, and database I/O.

## Resources

- [unittest — Unit testing framework](https://docs.python.org/3/library/unittest.html)
- [unittest.mock — mock object library](https://docs.python.org/3/library/unittest.mock.html)
- [How to mock a readonly property with mock?](https://stackoverflow.com/questions/15011399/how-to-mock-a-readonly-property-with-mock)
- [parameterized](https://pypi.org/project/parameterized/)
- [Memoization](https://en.wikipedia.org/wiki/Memoization)

## Learning Objectives

By the end of this project, you should be able to explain the following concepts:

### General

- The difference between unit and integration tests.
- How to write effective unit tests for individual functions or methods.
- How to implement integration tests to verify the interaction between various components.
- Common testing patterns such as mocking, parametrization, and fixtures.
- How to use the `unittest` framework and `mock` library for testing in Python.
- How to execute tests using the `unittest` framework.

## Requirements

### Python Scripts

- All files will be interpreted/compiled on Ubuntu 18.04 LTS using Python 3.7.
- All files should end with a new line.
- The first line of all files should be exactly `#!/usr/bin/env python3`.
- A `README.md` file, at the root of the folder of the project, is mandatory.
- Code should use the `pycodestyle` style (version 2.5).
- All files must be executable.
- All modules should have documentation: `python3 -c 'print(__import__("my_module").__doc__)'`.
- All classes should have documentation: `python3 -c 'print(__import__("my_module").MyClass.__doc__)'`.
- All functions (inside and outside a class) should have documentation: `python3 -c 'print(__import__("my_module").my_function.__doc__)'` and `python3 -c 'print(__import__("my_module").MyClass.my_function.__doc__)'`.
- Documentation should be a real sentence explaining the purpose of the module, class, or method.
- All functions and coroutines must be type-annotated.

### Required Files

- `utils.py`: Contains utility functions used across the project.
- `client.py`: Implements the client logic for interacting with external services.
- `fixtures.py`: Provides fixtures used for setting up test data.

## Running Tests

To execute your tests, run the following command:

```bash
$ python -m unittest path/to/test_file.py
```

### Key Points Covered in the README

1. **Background Context**: Explains the purpose of unit and integration testing, highlighting their differences and when each should be used.

2. **Resources**: Provides links to helpful documentation and articles that can aid in understanding and implementing testing.

3. **Learning Objectives**: Summarizes the knowledge and skills that should be acquired by the end of the project.

4. **Requirements**: Lists the specific requirements for Python scripts, including coding style and documentation guidelines.

5. **Required Files**: Mentions the files necessary for the project and their roles.

6. **Running Tests**: Provides a command for executing tests using the `unittest` framework.

7. **Author**: Aman Hablu
