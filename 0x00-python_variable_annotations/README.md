# ALX Backend Python

## 0x00. Python - Variable Annotations

### Description

This project is part of the ALX Backend Python curriculum. It focuses on understanding and implementing type annotations in Python. The tasks include creating functions with type annotations, defining variables with type annotations, and working with complex types and duck typing.

### Learning Objectives

By the end of this project, you should be able to:

- Understand type annotations in Python 3.
- Use type annotations to specify function signatures and variable types.
- Explain duck typing.
- Validate code with mypy.

### Requirements

- Allowed editors: `vi`, `vim`, `emacs`.
- All files will be interpreted/compiled on Ubuntu 18.04 LTS using `python3` (version 3.7).
- All files should end with a new line.
- The first line of all files should be exactly `#!/usr/bin/env python3`.
- A `README.md` file at the root of the project is mandatory.
- Code should use the `pycodestyle` style (version 2.5).
- All files must be executable.
- The length of files will be tested using `wc`.
- All modules should have a documentation string.
- All classes should have a documentation string.
- All functions (inside and outside a class) should have a documentation string.

### Tasks

#### 0. Basic annotations - add

Write a type-annotated function `add` that takes two floats `a` and `b` as arguments and returns their sum as a float.

#### 1. Basic annotations - concat

Write a type-annotated function `concat` that takes two strings `str1` and `str2` as arguments and returns a concatenated string.

#### 2. Basic annotations - floor

Write a type-annotated function `floor` which takes a float `n` as an argument and returns the floor of the float.

#### 3. Basic annotations - to string

Write a type-annotated function `to_str` that takes a float `n` as an argument and returns the string representation of the float.

#### 4. Define variables

Define and annotate the following variables with the specified values:
- `a`: an integer with a value of 1.
- `pi`: a float with a value of 3.14.
- `i_understand_annotations`: a boolean with a value of True.
- `school`: a string with a value of “Holberton”.

#### 5. Complex types - list of floats

Write a type-annotated function `sum_list` which takes a list `input_list` of floats as an argument and returns their sum as a float.

#### 6. Complex types - mixed list

Write a type-annotated function `sum_mixed_list` which takes a list `mxd_lst` of integers and floats and returns their sum as a float.

#### 7. Complex types - string and int/float to tuple

Write a type-annotated function `to_kv` that takes a string `k` and an int OR float `v` as arguments and returns a tuple. The first element of the tuple is the string `k`. The second element is the square of the int/float `v` and should be annotated as a float.

#### 8. Complex types - functions

Write a type-annotated function `make_multiplier` that takes a float `multiplier` as an argument and returns a function that multiplies a float by `multiplier`.

#### 9. Let's duck type an iterable object

Annotate the function `element_length`’s parameters and return values with the appropriate types.

#### 10. Duck typing - first element of a sequence

Augment the function `safe_first_element` with the correct duck-typed annotations.

#### 11. More involved type annotations

Add type annotations to the function `safely_get_value`.

#### 12. Type Checking

Use `mypy` to validate the following piece of code and apply any necessary changes:

### Installation

To run these scripts, ensure you have Python 3.7 installed. You may also want to set up a virtual environment.

```bash
# Clone the repository
git clone https://github.com/Emakiflom/alx-backend-python.git

# Navigate to the project directory
cd alx-backend-python/0x00-python_variable_annotations

# (Optional) Create a virtual environment
python3 -m venv venv
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

