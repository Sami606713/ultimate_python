# Variables and Datatypes
- Varable is just like a container that is used to store some data.
# Example
- a=5  `This varaible can store integer`.
- b=45.90  `This variable can store floating point nbr`.
- c='sami'  `This variable can store string means combination of characters.`
- d=True/False  `This varaiable can store boolean data like True or False`.
- e=None  `This variable can store None mean they are used to create a empty variable`

- `Type Fun`
- `Types` fun are used to check the datatype of variable

# Variable Declearation Rules
### 1. Variable Names
- Variable names must start with a letter (a-z, A-Z) or an underscore (_).
- The rest of the variable name can include letters, digits (0-9), and underscores.
- Variable names are case-sensitive (`age`, `Age`, and `AGE` are different variables).

### 2. Naming Conventions
- Use descriptive names to make your code more readable and understandable.
  - **Good**: `age`, `total_amount`, `user_name`
  - **Bad**: `a`, `amt`, `u`
- Use snake_case for variable names, which is the standard convention in Python.
  - **Example**: `user_age`, `total_sum`
- Avoid using reserved keywords as variable names. Examples of reserved keywords include `False`, `None`, `True`, `and`, `as`, `assert`, `async`, `await`, `break`, `class`, `continue`, `def`, `del`, `elif`, `else`, `except`, `finally`, `for`, `from`, `global`, `if`, `import`, `in`, `is`, `lambda`, `nonlocal`, `not`, `or`, `pass`, `raise`, `return`, `try`, `while`, `with`, `yield`.

### 3. Dynamic Typing
- Python is dynamically typed, meaning you do not need to declare the type of a variable when you create one. The type is inferred from the value assigned to it.
  ```python
  age = 25         # integer
  name = "Alice"   # string
  price = 19.99    # float
  is_student=False  # Boolean