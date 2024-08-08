# E-tonix desktop app
E-Tonix Desktop Application
Description
E-Tonix is a comprehensive desktop application developed using Python's Tkinter library for managing home and inventory data. The application provides functionalities to track and manage home-related data, such as arrival dates, names, devices, issues, and more. It also includes inventory management features and allows for generating daily reports in both Excel and PDF formats.

Features
Login System: Secure login with username and password.
Home Management: Add, edit, delete, and view home-related data.
Inventory Management: Add, edit, delete, and view inventory data.
Pending Tasks Management: View and manage tasks that are pending.
Search Functionality: Search for home and inventory entries.
Generate Daily Report: Export daily reports to Excel and PDF formats.
Date and Time Display: Real-time update of date and time across various sections.
Libraries Used
tkinter: For the GUI application interface.
sqlite3: For database management.
fpdf: For PDF generation.
openpyxl: For Excel file operations.
datetime: For handling date and time functionalities. 

Certainly! Here’s a template for a README file that you can use for your GitHub repository. This README covers your project, which involves a desktop application using Tkinter, SQLite, and other libraries.

E-Tonix Desktop Application
Description
E-Tonix is a comprehensive desktop application developed using Python's Tkinter library for managing home and inventory data. The application provides functionalities to track and manage home-related data, such as arrival dates, names, devices, issues, and more. It also includes inventory management features and allows for generating daily reports in both Excel and PDF formats.

Features
Login System: Secure login with username and password.
Home Management: Add, edit, delete, and view home-related data.
Inventory Management: Add, edit, delete, and view inventory data.
Pending Tasks Management: View and manage tasks that are pending.
Search Functionality: Search for home and inventory entries.
Generate Daily Report: Export daily reports to Excel and PDF formats.
Date and Time Display: Real-time update of date and time across various sections.
Libraries Used
tkinter: For the GUI application interface.
sqlite3: For database management.
fpdf: For PDF generation.
openpyxl: For Excel file operations.
datetime: For handling date and time functionalities.
Installation
Clone the Repository:

bash
Copy code
git clone https://github.com/yourusername/etonic-desktop-app.git
cd etonic-desktop-app
Install Required Packages:
Ensure you have Python 3.x installed. You can use pip to install the required packages.

bash
Copy code
pip install fpdf openpyxl
Usage
Run the Application:

bash
Copy code
python main.py
Login:
Use the following credentials for login:

Username: admin
Password: AdminE
Navigating the Application:

Home: View and manage home-related data.
Inventory: View and manage inventory data.
Pending Tasks: View pending tasks.
Generating Reports:

Click on "Generate Daily Report" to export the report for the current date in Excel and PDF formats.
Database
The application uses SQLite for database management. The following databases are created:

etonic.db - For managing home data.
inventory.db - For managing inventory data.


Contact
For any inquiries or support, please contact your email.
