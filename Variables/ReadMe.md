// Use uppercase to define constants. 
EXAMPLE_COUNT2 = 10 // This tells the team that it is a constant and should not be changed.

- Variable names should be all lower case and words seperated by underscore.
example_count = 1000 // This is a integer

example_rating = 4.99 // This is a float

is_example = True // This is a boolean

example_name = "Python" // String (str)
example_name2 = 'Python' / String (str) single quote


example_name3 = """
Multiple
Python
Lines
""" // String (str) triple quote

// Lists
temp_list = [1, 2, 3, 4, 5]
temp_list.append(6) / 6 will be added at the end of the list.

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

List is mutable / example temp

// Get memory location of a variable or object.
print(id(variable_name_here))
