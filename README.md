Password Generator (Tkinter)

A desktop-based Password Generator built with Python and the Tkinter library. This tool allows users to generate secure, randomized passwords with specific constraints, such as minimum counts for numbers and special characters.
🚀 Features

    Customizable Length: Set password length between 4 and 32 characters.

    Character Sets: Toggle options to include digits (0-9), uppercase letters (A-Z), and symbols (!@#$%^&*).

    Enforced Minimums: Guarantee a specific number of digits and special characters within the total length.

    Input Validation: Prevents generation if minimum requirements exceed the total password length.

    Modern UI: A clean, dark-themed interface built for readability.

Prerequisites

To run this application, you need Python 3.x installed on your system.
The application uses the following libraries:

    tkinter (Usually bundled with Python)

    random (Standard library)

    string (Standard library)


How to Use

    Set Length: Use the first spinbox to choose how long you want your password to be.

    Toggle Requirements: Check the boxes for Numbers, Uppercase letters, or Symbols to include them in the pool of random characters.

    Set Minimums: Specify exactly how many numbers and special characters must appear in the result.

    Generate: Click the Generate Password button to view your result at the bottom of the window.

Code Structure

    get_password(): The core logic function that handles string concatenation, character selection, and shuffling to ensure randomness.

    buttonclicked(): The UI controller that fetches values from the Tkinter variables, validates the logic, and updates the display.

    Root Window: Configured with a dark background (#1e1e2f) and centered layout for a modern feel.
