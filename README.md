<!-- # CD

A hands-on project created to learn, experiment with, and demonstrate core concepts and best practices.
import pandas as pd

# Create a simple DataFrame

data = {
"name": ["Alice", "Bob", "Charlie"],
"age": [25, 30, 35],
"city": ["New York", "London", "Paris"]
}

df = pd.DataFrame(data)

# Display the DataFrame

print(df) -->

from datetime import datetime

def greet(name):
hour = datetime.now().hour

    if hour < 12:
        greeting = "Good morning"
    elif hour < 18:
        greeting = "Good afternoon"
    else:
        greeting = "Good evening"

    return f"{greeting}, {name}!"

def main():
name = input("Enter your name: ")
message = greet(name)
print(message)

if **name** == "**main**":
main()
