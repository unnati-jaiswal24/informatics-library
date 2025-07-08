# informatics-library
A simple console‑based Library Management System built with Python and MySQL. Allows admins to manage members, books, book issues, and returns.

## Features

- 🔐 **Secure Login**  
  Admins must authenticate using username/password before accessing the system.

- 👥 **Member Management**  
  - Add new members (ID, name, phone, email)  
  - Delete existing members  
  - View a formatted list of all registered members

- 📖 **Book Management**  
  - Add new books (Book ID, title, author, publisher, cost)  
  - Delete existing books  
  - List all books with details

- 🏷️ **Issue & Return Books**  
  - Issue a book to a member if available, recording the issue date  
  - Return a book, record return date, and move record to return log  

- 📋 **Reporting**  
  - View list of currently issued books  
  - View history of returned books  

### Prerequisites

- Python 3.x  
- `mysql-connector-python` library (`pip install mysql-connector-python`)  
- MySQL database with these tables:

[click here to view live demo]( https://unnati-jaiswal24.github.io/informatics-library/)
