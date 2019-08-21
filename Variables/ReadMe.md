- Variable names should be all lower case and words seperated by underscore.
example_count = 1000 // This is a integer

example_rating = 4.99

is_example = True

example_name = "Python"
example_name2 = 'Python'


example_name3 = """
Multiple
Python
Lines
"""

// initialize multiple variables same time.
x, y, z = 1, 2, 3
/ result is: x = 1, y = 2, z = 3
/ or same result
x = y = z = 1
/ Result of x, y, z will be 1

// Get type of variable
type(variable_name)
Example = print(variable_name)

// If you would like to include variable type do it this way
example: example: str = "test"
example: example2: int = 10
/ This will have no impact on the code just for user friendly reading.
/ Some linters like mypy will complain when you set variable that was already defined to int to string.

// Mutable and Immutable Types
