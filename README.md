# PURPOSE OF THE PROGRAM:
# This program asks the user to enter their name and then displays
# a friendly greeting message using the entered name.

# PURPOSE OF THE REPOSITORY:
# This repository is created to store simple Python programs for beginners.
# It helps learners understand basic concepts like input, output,
# variables, and string formatting through easy examples.

# EXPLANATION:
# The input() function displays a prompt asking the user for their name.
# Whatever the user types is stored in the variable called 'name'.

name = input("Enter your name: ")

# The print() function displays output on the screen.
# The 'f' before the string means formatted string (f-string),
# which allows the value of 'name' to be inserted into the message.

print(f"Hello, {name}! Nice to meet you.")
