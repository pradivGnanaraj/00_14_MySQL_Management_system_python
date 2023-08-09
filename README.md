
# Student Management System with PyQt6

This repository contains a Python script that implements a Student Management System using the PyQt6 library. The application offers an intuitive graphical interface for managing student records within a MySQL database. Students can be added, edited, searched for, and deleted using this system.

## Features

- **Graphical User Interface:** The application uses PyQt6 to create a user-friendly interface, enhancing the user experience.

- **Data Persistence:** Student records are stored in a MySQL database, allowing efficient storage and retrieval of information.

- **Record Management:** Users can perform various operations on student records, including adding, editing, searching, and deleting.

## Installation and Usage

1. Install the required dependencies using the following command:

   ```bash
   pip install PyQt6 mysql-connector-python
   ```

2. Ensure that you have a MySQL database available for the application.

3. Run the script using the following command:

   ```bash
   python main.py
   ```

4. Interact with the graphical interface to manage student records.

## Structure

- `main.py`: The main script that creates the application window, handles interactions, and interfaces with the database.
- `icons/`: A folder containing icons used for menu actions.

## Database Configuration

The application is set up to connect to a MySQL database. Modify the `DatabaseConnection` class in `main.py` to match your database credentials.

## Usage

1. Launch the application using the provided instructions.

2. Use the interface to perform the following actions:
   - **Add Student:** Add a new student record to the database.
   - **Search:** Search for students by name.
   - **Edit:** Edit existing student records.
   - **Delete:** Delete student records.

## Note

This application was created as part of "The Python Mega Course" and can be customized or reused according to your needs. Feel free to modify the codebase and extend its functionality as desired.

---
