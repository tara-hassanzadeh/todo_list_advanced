# Advanced To-Do List in Python

This project is an enhanced To-Do List application written in Python. It supports task management with priorities and due dates, persistent data storage in JSON format, and basic user interaction via command line.

## Features

- Add tasks with descriptions, priority levels (low, medium, high), and due dates.
- Mark tasks as done or not done.
- Delete tasks from the list.
- Persistent storage of tasks in a JSON file (`tasks.json`), which maintains data between sessions.
- Input validation for dates and menu options.

## Usage

Run the Python script to start the application. Tasks will be loaded from and saved to the `tasks.json` file automatically.

## Sample Output

A sample `tasks.json` file is included in the repository, showcasing the format of stored tasks after running the program.

```json
[
  {
    "task": "Complete project report",
    "priority": "high",
    "due_date": "2025-08-01",
    "done": false
  },
  {
    "task": "Review Python tutorials",
    "priority": "medium",
    "due_date": "2025-07-20",
    "done": true
  }
]
