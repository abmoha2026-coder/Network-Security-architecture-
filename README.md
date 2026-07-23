# Basic bot_program

# Features

# Greets the user and asks for their name and age
# Stores the inputs in variables
# Uses string concatenation to format messages
# Display personalized greetings with f"strings
# calculate the age difference between the user and a bot (age 3)

print("Hello, what is your name?")
print("What is your age?")


# Create variables name, age
name = input("Enter your name?") 

# greet user

name = "Hello" + name
print(name) 

# call age
age = input("Enter your age?") 
age = "You are " + age
print(age) 
# call name and age using f "string
print(f"Hello {name}, you are {age} years old") 

# compare age 

bot_age = 3
age_difference = age - bot_age

print(f"You are {age_difference}, \n I am just "
{bot_age} years old") 






