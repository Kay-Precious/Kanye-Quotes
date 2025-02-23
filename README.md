# Kanye-Quotes

A simple GUI application built with Tkinter that displays random Kanye West quotes. Each time the user clicks the Kanye button, a new quote is fetched from the Kanye REST API and displayed on the screen.

Requirements

- Python 3.x
- Tkinter library
- requests library
- Kanye REST API

Installation

1. Clone the repository using git clone
2. Install required libraries using pip install tkinter requests
3. Run the application using python kanye_quotes.py

Code Structure

The code is structured into the following functions:

- get_quote(): Fetches a random Kanye quote from the Kanye REST API and updates the quote text on the screen
- Main application: Creates the GUI window, sets up the background image, quote text, and Kanye button

API Documentation

- Kanye REST API: https://api.kanye.rest

Usage

1. Run the application using python kanye_quotes.py
2. Click the Kanye button to display a new quote

Note: Make your device is connected to the internet. If not, the code will raise an error.
