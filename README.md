# Data Entry System

## Description
This Data Entry System is a desktop application built with Python and Tkinter. It provides a user-friendly interface for entering, managing, and storing student information in a SQLite database.

## Features
- User Information Entry: Collect details like name, email, age, and nationality
- Course Registration: Record course details and registration status
- CRUD Operations: Create, Read, Update, and Delete student records
- Data Validation: Ensure data integrity with input validation
- Database Integration: Store and retrieve data using SQLite
- User-friendly GUI: Built with ttkbootstrap for an enhanced look and feel

## Requirements
- Python 3.x
- tkinter
- ttkbootstrap
- sqlite3

## Installation
1. Clone this repository or download the source code.
2. Navigate to the project directory:
3. Create a virtual environment (optional but recommended):
   ```
   python -m venv venv
    # On Windows use, `venv\Scripts\activate`
    # On Mac & Linux use, source venv/bin/activate 
   ```
4. Install the required packages using the requirements.txt file:
   ```
   pip install -r requirements.txt
   ```
  

## Usage
1. Run the main script:
   ```
   python main.py
   ```
2. Use the GUI to enter student information and perform database operations.

## File Structure
- `main.ipynb`: Jupyter Notebook containing the application code
- `main.py`: The main application script
- `values.py`: Contains predefined values for dropdowns
- `users.ico`: Icon file for the application window
- `data.db`: SQLite database file (created automatically when the app runs)
- `requirements.txt`: List of Python package dependencies

## Contributing
Contributions, issues, and feature requests are welcome.

## License
This project is licensed under the MIT License:

MIT License

Copyright (c) 2024 Dennis Abinayo

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## Author
Dennis Abinayo

## Acknowledgments
- ttkbootstrap for the modern UI elements
- SQLite for the lightweight database solution