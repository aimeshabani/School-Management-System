

School Management System

A comprehensive School Management System designed to streamline school administration processes, including managing teacher data, student records, finances, and more. The system also generates professional documents like report cards, payment receipts, and financial reports, with advanced features for analysis, scheduling, and security.


---

Features

1. Student Management

Register students with 16 required details (per UNEB standards), including photos captured via OpenCV (cv2 library).

Sorting options:

By courses, identifying top-performing students or those needing improvement.

By disabilities, tracking special needs for inclusive education.

By specific criteria, such as finding an orphan excelling in science.


Performance Analytics:

Analyze subject-wise performance, including failure rates and class performance percentages.



2. Teacher Management

Each teacher has a unique account with:

Personal details (e.g., date of birth, next of kin).

Password-protected access for secure use.


Payment Management:

Track how much the institution owes each teacher.

Teachers confirm their salary using a password.



3. Dynamic Timetable Management

Import timetables for specific months or days.

Set reminders for exams, events, or deadlines.


4. Financial Management and Spending Tracker

Track Finances:

Monitor:

Income: How much the institution gained.

Expenses: How much was spent and for what.

Balance: Remaining amount in the bank.


Generate financial reports for any time range:

Daily, weekly, monthly, or yearly.

Print hard copies with the school logo, headers, and contracts.



Debt Management:

Student Debt Reports:

List students who haven’t paid.

Filter by:

Specific class or grade.

Debt range (e.g., debts above $10).

Attributes like disabilities, gender, or age group.


Print official institution documents for reporting purposes.



5. Role-Based Access Control

Three user roles:

Secretary: Access to secretarial tasks only.

Financial Staff (BASA): Access to financial data only.

Admin: Full system access.


Data Security:

All data is stored on an FTP local server:

No data is stored on individual computers.

Ensures continuity and security in case of theft or hardware failure.




6. Custom Reporting

Generate detailed report cards:

Includes marks, aggregates, and remarks.

QR code integration for tracking.


Add motivational elements like remarks and initials to student reports.


7. Automation

Automatically handles all calculations, including:

Salary balances.

Class debt totals.

Spending analysis.

Performance metrics.




---

Technologies Used

Frontend: kivy

Backend: Python

Database: FTP server-based storage

Libraries: OpenCV (cv2) for photo capture



---

Installation

1. Clone the Repository:

git clone https://github.com/aimeshabani/school-management-system.git


2. Navigate to the Project Directory:

cd school-management-system


3. Install Dependencies:

pip install -r requirements.txt


4. Configure the FTP Server:

Ensure you have an FTP server (router-based or dedicated) set up for secure data storage.



5. Run the Application:

python main.py




---

Usage

Role-Based Login:

Login as:

Secretary: Access secretarial tasks.

Financial Staff: Access financial tasks.

Admin: Access all tasks.



Dynamic Features:

Import, manage, and set reminders for timetables.

Analyze and filter student or teacher data for informed decision-making.


Spending Tracker:

Generate and print financial reports (daily, weekly, monthly, yearly).

Monitor all income, expenses, and balances.

Print professional financial documents for audits or reviews.



---

Screenshots

Include screenshots to showcase:

1. Report cards.


2. Dynamic timetable.


3. Spending tracker and financial reports.


4. Role-based user interface.




---

Contribution

Contributions are welcome! Please:

1. Fork the repository.


2. Create a pull request for any changes or new features.




---

License

This project is licensed under the MIT License.


---

Author

Shabani Aime

Contact: aimeshabani@gmail.com




