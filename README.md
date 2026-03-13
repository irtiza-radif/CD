from datetime import datetime


def greet_user(name):
    """Return a greeting based on the current time."""
    hour = datetime.now().hour

    if hour < 12:
        greeting = "Good morning"
    elif hour < 18:
        greeting = "Good afternoon"
    else:
        greeting = "Good evening"

    return f"{greeting}, {name}! Welcome to this Python project."


def main():
    """Main program execution."""
    name = input("Enter your name: ")
    message = greet_user(name)
    print(message)


if __name__ == "__main__":
    main()
