# it23817630_ITPM_assignment1
it23817630_ITPM_assignment1
## Test Automation - Playwright

This project is used to automate testing for a web-based chat translator using Playwright and Python.

### Setup

First install required libraries:

pip install playwright openpyxl

Then install browser dependencies:

playwright install

### How to Run

Go to the project folder and run:

python test_automation.py --excel "Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --headless

### Excel File

The Excel file should include these columns:

TC ID, Input length type, Input, Expected Output, Actual Output, Result

### Important

* Do not open the Excel file while running the script
* Check the sheet name is correct
* Remove headless mode if you want to see the browser
