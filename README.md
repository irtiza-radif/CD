# CD

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

print(df)
