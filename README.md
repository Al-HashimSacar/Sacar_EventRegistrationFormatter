# Sacar_EventRegistrationFormatter
# Event Registration Formatter

## Project Description
This Python program helps students register for school events cleanly and accurately. It accepts raw user inputs for a student's name, section, event title, and event date, cleans messy spacing or capitalization, and outputs a standardized registration summary.

## Features
- **Input Cleaning:** Removes extra leading and trailing whitespace using `.strip()`.
- **Text Standardization:** Formats names and event titles into Title Case (`.title()`) and converts name codes and sections to Uppercase (`.upper()`).
- **Date Formatting:** Converts numeric year, month, and day inputs into a readable date format (e.g., `June 3, 2026`) using Python's `datetime` module.

## How to Run the Program
1. Ensure Python 3 is installed on your computer.
2. Download or clone this repository.
3. Open your terminal or command prompt and navigate to the project folder.
4. Run the program using:
   ```bash
   python event_registration.py
   ```
5. Follow the on-screen prompts to enter your registration details.

## Version History
- **Version 1:** Basic input collection and plain text output.
- **Version 2:** Added string cleaning and formatting methods (`strip()`, `title()`, `upper()`).
- **Version 3:** Integrated Python's `datetime` module to format the event date cleanly.

## Author
- **Name:** Al-Hashim A. Sacar
- **Section:** Sampaguita

# Reflection:

# Developing the Event Registration Formatter in Python taught me how small programming features can turn messy raw inputs into clean, reliable, and professional records. When people fill out registration forms quickly, they often add accidental spaces, forget to capitalize names properly, or enter dates in inconsistent formats. Through this activity, I saw firsthand how a program can automatically clean and standardize that data before displaying it.

# Using Python’s built-in string methods made a huge difference in the quality of my output. By applying .strip(), my program removed unnecessary spaces before and after user entries. Combining .title() for names and event titles with .upper() for sections and name codes ensured that inputs like "  juan dela cruz " and "magnesium" were consistently formatted into "Juan Dela Cruz" and "MAGNESIUM". Integrating the datetime module further improved the program by converting numeric inputs for the year, month, and day into a clear, readable date format like "June 3, 2026" instead of plain numbers separated by slashes.

# Building the project across three separate versions on GitHub also showed me the value of step-by-step software development. Starting with basic input and output in Version 1 allowed me to verify that the core logic worked before adding string formatting in Version 2 and date formatting in Version 3. Testing each version separately made it easier to spot small issues—such as removing leading zeros on single-digit days—and kept my code organized. Overall, this project strengthened my understanding of Python string manipulation, date formatting, and how version control helps track the growth of a program from start to finish.
