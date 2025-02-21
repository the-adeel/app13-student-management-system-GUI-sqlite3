# Student Management System

## Overview
The **Student Management System** is a simple yet effective application built using **SQLite3** to manage student records. It allows users to perform CRUD (Create, Read, Update, Delete) operations on student data efficiently.

## Features
- Add new student records
- View all student records
- Update student details
- Delete student records
- Search for students by name or ID
- User-friendly interface

## Technologies Used
- **Python** (for backend logic)
- **SQLite3** (for database management)

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/the-adeel/app13-student-management-system-GUI-sqlite3.git
   ```
2. Navigate to the project directory:
   ```bash
   cd app13-student-management-system-GUI-sqlite3
   ```
3. Install dependencies (if any):
   ```bash
   pip install -r requirements.txt
   ```
4. Run the application:
   ```bash
   python main.py
   ```

## Database Structure
The SQLite3 database contains a table named `students` with the following structure:

| Column Name  | Data Type  | Description |
|-------------|-----------|-------------|
| id          | INTEGER (Primary Key, Auto Increment) | Unique student ID |
| name        | TEXT      | Student's full name |
| course      | TEXT      | Student's course enrolled |
| contact     | INTEGER   | Student's Contact |

## Usage
- Run the script to start the system.
- Choose from the available options (Add, View, Update, Delete, Search).
- Follow the prompts to manage student records.

## Future Enhancements
- Implement a GUI using Tkinter or PyQt
- Add authentication for secure access
- Generate reports in CSV or PDF format
- Cloud-based database integration

## License
Feel free to modify and distribute it.

## Contact
For queries or contributions, contact:
- **Adeel**
- Email: adeelmughal246@gmail.com
- GitHub: [the-adeel](https://github.com/the-adeel)
