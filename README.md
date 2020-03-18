# data_scientist
# Type_conversion
# Definition of savings and result
savings = 100\
result = 100 * 1.10 ** 7

# Fix the printout
print("I started with $" + savings + " and now have $" + result + ". Awesome!")\
print("I started with $" + str(savings) + " and now have $" + str(result) + ". Awesome!")

To fix the error, you'll need to explicitly convert the types of your variables. More specifically, you'll need str(), to convert a value into a string. str(savings), for example, will convert the integer savings to a string.
