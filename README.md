

**School Management System**

This is a comprehensive School Management System designed to streamline and enhance school administration processes. The system manages teacher data, student records, financial transactions, and more. It generates professional documents like report cards, payment receipts, and financial reports while offering advanced features for data analysis, scheduling, and security.

---

**Features**

1. *Student Management:*

Register students with 16 required details (per UNEB standards), including photos captured via OpenCV (cv2 library).

Sort students by:

Courses: Identify top-performing students or those needing improvement.

Disabilities: Manage and track special needs for inclusive education.

Specific Criteria: For example, find an orphan excelling in science.


Analyze subject-wise performance, including failure rates and class performance percentages.



2. *Teacher Management:*

Assign each teacher a unique account with:

Personal details (e.g., date of birth, next of kin).

Password protection for secure access.


Manage teacher payments:

Track how much the institution owes each teacher.

Teachers confirm salaries using their passwords.



2. *Dynamic Timetable Management:*

Import timetables for specific months or days.

Set reminders for exams, events, or important deadlines.


Financial Management and Spending Tracker:

Track Income and Expenses:

Monitor how much has been gained, spent, and the remaining balance in the institution’s account.

Generate financial reports ranging from daily to yearly summaries.


3. *Advanced Financial Reporting:*

Print detailed hard copies of financial data, including school logo, headers, and contracts, for any specific day, week, or month.

Generate debt reports:

List students who have not yet paid.

Filter debts by:

Specific class or grade.

Amount owed (e.g., debts above $10).

Attributes like disabilities, gender, age group, etc.


Print institution-approved documents for internal or external use.




**User Roles and Security:**

Supports three user roles:

Secretary: Access to secretarial tasks only.

Financial Staff (BASA): Access to financial data only.

Admin: Full system access.


Data is stored securely on an FTP local server (e.g., router-based or dedicated server):

No data is stored on individual computers.

Ensures continuity and security in case of theft or hardware failure.



**Custom Reporting:**

Generate detailed report cards with marks, aggregates, and remarks.

Add motivational elements like remarks and initials to student reports.

QR code integration for modernized document tracking.


Automation:

The system handles all calculations (e.g., salary balances, class debt totals, spending analysis, and performance metrics) automatically.


Technologies Used

Frontend: kivy

Backend: Python

Database: FTP server-based storage

Libraries: OpenCV (cv2) for photo capture


**Installation**

1. Clone the repository:

git clone https://github.com/aimeshabani/school-management-system.git


2. Navigate to the project directory:

cd school-management-system


3. Install dependencies:

pip install -r requirements.txt


4. Configure the FTP server for data storage.


5. Run the application:

python main.py



**Usage**

Role-Based Login:

Login as Secretary, Financial Staff, or Admin to access relevant features.


Spending Tracker:

Generate reports for any time range (daily, weekly, monthly, yearly).

Monitor all income, expenses, and account balances.

Print professional documents for financial records or audits.


Dynamic Filtering and Reporting:

Find specific groups of students or teachers based on attributes like debt, performance, or demographics.



*Screenshots*

Include screenshots of the following:

Report cards

Dynamic timetable

Spending tracker and financial reports

User role management


Contribution

Contributions are welcome! Please fork the repository and create a pull request for any changes or new features.

License

This project is licensed under the MIT License.

Author

Shabani Aime

Contact: aimeshabani@gmail.com

