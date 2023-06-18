# Gruyere Vulnerability Exploitation

This project showcases the automated exploitation of vulnerabilities in the Gruyere vulnerable-by-design application. The code provided allows candidates to demonstrate their ability to create code to automatically exploit the well-documented vulnerabilities.

## Usage of Google Gruyere Vulnerable Application

To perform the vulnerability exploitation, follow these steps:

1. Visit the Google Gruyere vulnerable application website: [Google Gruyere](https://google-gruyere.appspot.com/)

2. Sign in using any Google account or create a new account.

3. Explore the vulnerable application to familiarize yourself with its features and vulnerabilities.

4. Use the code and tools provided in this project to create automated exploits for the documented vulnerabilities.

## Requirements

To run the code and execute the automated exploits, ensure you have the following prerequisites:

- Python 3.x
- `requests` library (`pip install requests`)
- `playwright` library (`pip install playwright`)
- `typer` library (`pip install typer`)

## Project Structure

The project includes the following files:

- `xssgg.py`: This script demonstrates a basic exploit for Gruyere's cross-site scripting (XSS) vulnerability. It sends a GET request to the vulnerable page and prints the response content.

- `test_xssgg.py`: This file contains a PyTest test case to verify that the request to the Gruyere application returns a successful response (status code 200).

## How to Run

1. Install the required libraries mentioned in the **Requirements** section.

2. Execute the `xssgg.py` script to exploit the XSS vulnerability in the Gruyere application.

    ```bash
    python xssgg.py
    ```

3. Run the PyTest test case to verify that the request to Gruyere returns a successful response.

    ```bash
    pytest test_xssgg.py
    ```

"**xssgg**" stands for **Cross-Site Scripting Google Gruyere**.
