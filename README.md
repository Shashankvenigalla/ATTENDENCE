# Attendance Tracker
This project is a simple attendance tracker that updates an Excel file (attendance.xlsx) with the attendance status of students. Each student's attendance is recorded as either present (1) or absent (0), and the total number of classes attended and the total number of classes are updated.

## Requirements
Python 3.x
openpyxl library
## Installation
Clone the repository:
git clone https://github.com/yourusername/attendance-tracker.git
cd attendance-tracker

## Create and activate a virtual environment (optional but recommended):
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`

## Install the required packages:
pip install openpyxl
## Ensure you have an attendance.xlsx file in the same directory as your script, with the following structure:

| Registration Number | Name     | Total Classes Attended | Total Classes |
|---------------------|----------|------------------------|---------------|
| 101                 | John Doe | 0                      | 0             |
| 102                 | Jane Doe | 0                      | 0             |

## Usage
Run the script:
python attendance_tracker.py

## Follow the prompts to enter attendance for each student:

Enter p for present.
Enter a for absent.
The script will update the attendance.xlsx file with the attendance status and the totals for each student.

## Example
Attendance for 2024-07-17:
Enter attendance for John Doe (101): (p)resent or (a)bsent: p
Enter attendance for Jane Doe (102): (p)resent or (a)bsent: a

Attendance updated successfully!
## Notes
The script automatically adds the date to the next available column in the Excel sheet.
The total number of classes and total classes attended are updated for each student.
## License
This project is licensed under the MIT License
