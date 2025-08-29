# Flask Project

A Flask web application with user authentication and database functionality.

## Setup

### Prerequisites
- Python 3.12.4
- Virtual Environment (already set up in `venv/`)

### Installation

1. **Activate the virtual environment:**
   ```powershell
   # On Windows PowerShell
   .\venv\Scripts\Activate.ps1
   
   # On Windows Command Prompt
   venv\Scripts\activate
   ```

2. **Verify dependencies are installed:**
   ```bash
   pip list
   ```

### Project Structure
```
├── .gitignore                 # Git ignore rules
├── requirements.txt           # Full project dependencies
├── requirements-flask.txt     # Essential Flask dependencies only
├── run.py                     # Application entry point
├── market/                    # Application package
│   ├── __init__.py           # Package initialization
│   ├── models.py             # Database models
│   ├── routes.py             # Application routes
│   └── templates/            # HTML templates
└── venv/                     # Virtual environment (ignored by git)
```

### Dependencies Installed
- **Flask 3.1.1** - Web framework
- **Flask-SQLAlchemy 3.1.1** - Database ORM
- **Flask-Login 0.6.3** - User authentication
- **Flask-WTF 1.2.2** - Form handling
- **Flask-Bcrypt 1.0.1** - Password hashing
- **Flask-Migrate 4.1.0** - Database migrations

### Usage

1. Activate virtual environment (see above)
2. Run the application:
   ```bash
   python run.py
   ```

### Development Notes

- The virtual environment (`venv/`) is ignored by git
- Use `requirements-flask.txt` for essential Flask dependencies
- Use `requirements.txt` for the full project dependencies (contains many additional packages)
- Always work within the activated virtual environment
