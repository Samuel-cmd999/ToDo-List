# To-Do List CLI Application

A simple command-line to-do list manager with JSON file persistence.

## Features

- Add tasks with priority levels (high, medium, low)
- List all tasks with status indicators
- Mark tasks as completed
- Delete individual tasks
- Clear all completed tasks
- Persistent storage using JSON

## Usage

```bash
# Add a new task
python todo.py add "Complete Python project" --priority high

# Add a task with default priority (medium)
python todo.py add "Read documentation"

# List all tasks
python todo.py list

# Mark task as completed (use task ID)
python todo.py complete 1

# Delete a task
python todo.py delete 2

# Clear all completed tasks
python todo.py clear

# Show help
python todo.py help
```

## Task Status Indicators

- ✓ = Completed
- ○ = Pending
- ! = High priority
- - = Medium priority
- ~ = Low priority

## Data Storage

Tasks are stored in `todos.json` in the same directory.
