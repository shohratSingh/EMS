# 🚀 Employee Management System (EMS)

A simple and interactive **Employee Management System** built in Python.  
This console-based application allows you to **add, view, and search employee records** using Python dictionaries and functions.

## 📚 Table of Contents

- [Features](#features)  
- [Technologies Used](#technologies-used)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Functions Overview](#functions-overview)  
- [Contributing](#contributing)  
- [License](#license)  

## ✅ Features

- **Add Employee** – Add employee details such as ID, name, age, department, and salary.  
- **View All Employees** – Display all employees in a clean tabular format.  
- **Search Employee** – Search for an employee using their unique ID.  
- **Input Validation** – Ensures ID, age, and salary are numeric and prevents blank inputs or duplicate IDs.  
- **User-Friendly Interface** – Provides clear instructions and helpful error messages.

## 💻 Technologies Used

| Component                | Description          |
|--------------------------|----------------------|
| Programming Language     | Python 3.x           |
| Data Storage             | Dictionaries         |
| Interface                | Console / CLI        |

## 🔧 Installation

1. Make sure **Python 3.x** is installed on your system.  
2. Clone the repository using Git:

   ```bash
   git clone https://github.com/shohratSingh/EMS.git
   ```

3. Navigate into the project folder:

   ```bash
   cd EMS
   ```

4. Run the Python script:

   ```bash
   python employee_management_system.py
   ```

## ▶️ Usage

Once the script is executed, the menu will appear like this:

```
1. Add Employee
2. View All Employees
3. Search for Employee
4. Exit
```

- Press **1** → Enter employee details to add a new record.  
- Press **2** → View all employee records in a table.  
- Press **3** → Enter employee ID to search for a record.  
- Press **4** → Exit the application.

## 📂 Functions Overview

| Function Name       | Description |
|---------------------|-------------|
| `add_employee()`    | Collects details, validates input, and adds a new employee. |
| `view_employees()`  | Displays all stored employees in a table format. |
| `search_employee()` | Searches for an employee using the ID and displays details. |
| `main_menu()`       | Runs the main menu loop and handles user choices. |

## 🤝 Contributing

Contributions are always welcome!  
You can help by:

- Adding features (Update/Delete employee, data storage in files or databases).  
- Improving validation and error handling.  
- Creating a GUI or web-based version.

Steps to contribute:

1. Fork the repository.  
2. Create a new branch: `git checkout -b feature-name`  
3. Commit your changes and push.  
4. Open a pull request.

## 📄 License

This project is **open-source** and free to use for learning and educational purposes.  
You may modify and distribute it with proper credit.

### ✅ Note:
This application stores data **temporarily in memory** only (Python dictionaries). All employee records will reset once the program is closed.
