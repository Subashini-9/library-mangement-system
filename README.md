# library-mangement-system
Link  https://subashini-9.github.io/library-mangement-system/
📚 Library Management System

A simple and user-friendly Library Management System developed using HTML, CSS, and JavaScript.
This project helps manage books, library members, book issuing, book returns, transactions, overdue books, and fines through a single web application.

---

🎯 Project Objective

The main objective of this project is to develop a digital library management system that makes it easier for an administrator to:

- Manage books
- Manage library members
- Issue books
- Return books
- Track transactions
- Identify overdue books
- Calculate fines
- Search books and members
- Store data in the browser

---

✨ Features

🔐 Admin Login

- Simple administrator login system
- Username: "admin"
- Password: "admin123"
- Logout functionality

🏠 Dashboard

Displays important library statistics:

- Total Books
- Available Books
- Issued Books
- Total Members

📚 Book Management

- Add new books
- Delete books
- Search books
- View book ID
- View book name
- View author
- View category
- Check book availability

👨‍🎓 Member Management

- Add library members
- Delete members
- Search members
- Store member ID
- Store name
- Store phone number
- Store email address

📖 Issue & Return

- Select an available book
- Select a member
- Set the due date
- Issue books
- Return books
- Automatically update book availability

📋 Transaction History

Records:

- Book details
- Member details
- Issue date
- Due date
- Return date
- Fine
- Transaction status

⚠️ Overdue Management

- Detects overdue books
- Calculates number of late days
- Calculates fine automatically

Fine policy: ₹5 per overdue day

🔍 Search

Search functionality is available for:

- Books
- Members
- Transactions

💾 Data Storage

The project uses Browser LocalStorage to save:

- Books
- Members
- Transactions

Therefore, the data remains available after refreshing the page on the same browser.

📱 Responsive Design

The interface is designed to work on:

- Desktop
- Laptop
- Tablet
- Mobile devices

---

🛠️ Technologies Used

Technology| Purpose
HTML5| Structure of the application
CSS3| Styling and responsive design
JavaScript| Application logic and functionality
LocalStorage| Browser-based data storage

---

📁 Project Structure

LibraryManagementSystem/
│
├── index.html
│
└── README.md

The complete application is contained in a single "index.html" file.

---

🚀 How to Run

Step 1

Download or clone this project.

Step 2

Open the project folder in Visual Studio Code.

Step 3

Open:

index.html

Step 4

Run the file using a web browser such as:

- Google Chrome
- Microsoft Edge
- Mozilla Firefox

You can also use the Live Server extension in VS Code.

---

🔑 Login Details

Username: admin
Password: admin123

«These are demo credentials for the frontend project.»

---

🔄 System Workflow

Admin Login
     ↓
Dashboard
     ↓
Manage Books / Members
     ↓
Issue Book
     ↓
Set Due Date
     ↓
Book Issued
     ↓
Return Book
     ↓
Fine Calculation
     ↓
Transaction History

---

📊 Main Modules

1. Admin Module

Responsible for accessing and managing the library system.

2. Book Module

Used to add, search, view, and delete books.

3. Member Module

Used to maintain member information.

4. Issue Module

Used to issue books to members and assign due dates.

5. Return Module

Used to return issued books and calculate overdue fines.

6. Transaction Module

Maintains the history of issued and returned books.

7. Overdue Module

Displays books that have passed their due date.

---

💰 Fine Calculation

The system calculates the fine based on the number of overdue days.

Fine = Number of Overdue Days × ₹5

Example

If a book is returned 3 days late:

Fine = 3 × ₹5
     = ₹15

---

💾 LocalStorage

This project uses JavaScript "localStorage" instead of a traditional database.

The following data is stored:

library_books
library_members
library_transactions

This makes the project simple to run without installing a database server.

---

✅ Advantages

- Easy to use
- Simple interface
- No database installation required
- Fast book searching
- Easy member management
- Automatic fine calculation
- Transaction tracking
- Responsive design
- Suitable for academic demonstration

---

⚠️ Limitations

This is a frontend-based academic project.

It does not currently include:

- MySQL database
- PHP/Java/Python backend
- Real multi-user authentication
- Cloud database
- Online deployment database
- Advanced security

The login credentials and data are handled on the client side.

---

🔮 Future Enhancements

The project can be further improved by adding:

- MySQL database
- Backend using Python Flask / Java Spring Boot / PHP
- Secure authentication
- Student login
- Librarian login
- Admin and librarian roles
- Book cover images
- ISBN management
- Book quantity management
- Email notifications for due dates
- PDF report generation
- Fine payment tracking
- Online book reservation
- Cloud database
- Advanced reports and analytics

---

👩‍💻 Project Type

Academic Mini Project

Project Name: Library Management System

Frontend: HTML, CSS, JavaScript

Storage: Browser LocalStorage

---

📄 License

This project is created for educational and academic purposes.
