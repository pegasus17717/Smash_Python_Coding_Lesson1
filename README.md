# Smash101_Python_Coding_Lesson1

“Hello, World!” — the timeless love letter from one coder to another, echoing across the globe… and maybe even reaching distant planets. 🌍👾

Welcome to Smash101 — a beginner-friendly repository designed to help absolute newcomers quickly grasp the fundamentals of Python and build a strong coding foundation with confidence.

Lesson #1 Content

First Rule, MUST Know how to use print in Python



Program #1 if statement (the conditonal grammar)
Temperature Game
temperature = 18
# if temperature >= 40:
#     print("The temperature is hot today")
# elif temperature <= 20:
#     print("The temperature is cold")
# else:
#     print ("The temperature is normal")

Program #2 While Loops
Car Game
command = ""
while True:
    command = input(">").lower()
    if command == "start":
        print("Car Started...")
    elif command == "stop":
        print("Car Stopped...")
    elif command == "help":
        print("""
        start - starts the car
        stop - stops the car
        quit - quits the app
        """)
    elif command == "quit":
        break
    else:
        print("Unknown")
