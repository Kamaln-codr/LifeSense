# LifeSense — Personal Life & Productivity Management System

LifeSense is a Python-based application designed to help users manage daily tasks, track study sessions, monitor habits, and track personal goals in one place.

The project uses MySQL for data storage and Python data analysis libraries to analyze records, visualize progress, and generate useful insights.

## Features

- **Task Management** — Manage tasks, priorities, deadlines, and completion status.
- **Study Tracking** — Record study sessions, durations, activities, and focus ratings.
- **Habit Tracking** — Track daily habits and calculate streaks.
- **Goal Tracking** — Set goals and monitor progress.
- **Data Analysis** — Analyze records using Pandas and NumPy.
- **Data Visualization** — Generate charts using Matplotlib.
- **Insights** — Generate simple observations using predefined rules.

## Tech Stack

- Python
- MariaDB / MySQL
- mysql-connector-python
- Pandas
- NumPy
- Matplotlib

## Setup

### 1. Clone the repository

```bash
git clone <repository-url>
cd LifeSense
```

### 2. Create a virtual environment

```bash
python -m venv lifesense-env
```

Activate it on Linux:

```bash
source lifesense-env/bin/activate
```

### 3. Install dependencies

```bash
python -m pip install --upgrade pip
python -m pip install mysql-connector-python pandas numpy matplotlib
```

### 4. Configure the database

Make sure your MariaDB/MySQL server is running and your LifeSense database and tables have been created.

Update the database connection settings in the Python configuration when implementation begins.

### 5. Run the application

The application entry point will be added during development.

## Database Tables

- `tasks`
- `studysession`
- `habits`
- `habitlogs`
- `goals`

## Project Status

**Currently in development.**

LifeSense is being developed as a Class XII Informatics Practices project for the academic session 2026–27.

## License

This project is intended for educational purposes.
