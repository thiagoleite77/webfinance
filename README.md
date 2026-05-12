# Financial Management System

A responsive web application for personal financial management built with HTML, CSS, and JavaScript.

This project was designed to provide a simple and intuitive experience for controlling personal finances directly in the browser, including mobile devices.

<img width="1907" height="937" alt="image" src="https://github.com/user-attachments/assets/cea53c15-5f6c-41a5-93eb-9439e51e2f06" />


## Features

### Financial Dashboard
- Total balance
- Total income
- Total expenses
- Total investments
- Automatic calculations based on selected period

### Financial Records
- Add income records
- Add expense records
- Add investment records
- Edit records
- Delete individual records

### Categories
- Expense categories
- Income categories
- Investment categories
- Create custom categories directly from the form

### Fixed Monthly Records
- Create recurring monthly records
- Supports:
  - Fixed expenses
  - Fixed income
  - Fixed investments
- Automatic monthly generation
- Enable or disable recurring records

### Filters
- Daily filter
- Weekly filter
- Monthly filter
- Full history filter

### Charts
- Expense distribution by category
- Financial overview
- Automatic updates based on selected period

### Financial Statement
- Complete transaction history
- Identifies:
  - Manual entries
  - Fixed monthly entries

### Mobile Friendly
- Responsive layout
- Optimized for smartphones and tablets

## Technologies Used

- HTML5
- CSS3
- Vanilla JavaScript
- LocalStorage API
- Chart.js

## Data Storage

All data is stored locally in the browser using LocalStorage.

No external database is required.

## Project Structure

```plaintext
project/
│
├── index.html
└── style.css


How to Run
Download the files
Keep both files in the same folder
Open index.html in your browser

No installation or server is required.

Important Notes

Because the application uses LocalStorage:

Data remains saved after refreshing the page
Data may be lost if browser storage is cleared
Data is device-specific
Incognito mode is not recommended
Future Improvements

Possible future features:

Firebase cloud synchronization
User authentication
Open Finance integration
PDF and Excel exports
Notifications and reminders
Multi-user support
Dark and light themes
Author

Thiago Leite de Souza
