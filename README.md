# Smart Attendance Management System

A web-based attendance system developed as a final year capstone project to digitize and streamline attendance tracking.

## Features
- Role-based access control (Admin, Teacher, Student)
- Real-time attendance tracking
- Automated reports
- Dashboard interfaces for different user roles
- Attendance status visualization
- Export reports to CSV

## Tech Stack
- Backend: Python with Flask framework
- Database: SQLite
- Frontend: HTML, CSS, JavaScript
- Styling: Bootstrap 5
- Icons: Bootstrap Icons

## Setup Instructions

### Prerequisites
- Python 3.8 or higher
- pip (Python package manager)

### Installation
1. Clone the repository:
   ```
   git clone https://github.com/Mohit-Bhole/Attendance-management-system.git
   cd attendance-management-system
   ```

2. Create and activate a virtual environment (recommended):
   ```
   # Windows
   python -m venv venv
   venv\Scripts\activate

   # macOS/Linux
   python3 -m venv venv
   source venv/bin/activate
   ```

3. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

4. Run the application:
   ```
   python app.py
   ```

5. Access the application at: `http://localhost:5000`

## Project Structure
```
attendance-system/
├── app.py               # Main Flask application
├── database.db          # SQLite database (created on first run)
├── requirements.txt     # Python dependencies
├── schema.sql           # Database schema
├── static/              # Static files
│   ├── css/             # CSS stylesheets
│   ├── js/              # JavaScript files
│   └── images/          # Images and icons
└── templates/           # HTML templates
    ├── base.html        # Base template with common structure
    ├── index.html       # Landing page
    ├── login.html       # Login page
    └── ... (other templates)
```
---


---
## License

This project is created as a capstone project for educational purposes. 


