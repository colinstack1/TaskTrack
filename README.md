# TaskTrack

TaskTrack is a command-line task manager created for CPS 310. The program allows users to view and add tasks through a simple menu in the terminal. Tasks are stored in a text file so they remain available after the program is closed and restarted.

## Current Features

* View all saved tasks in a numbered list
* Add new tasks to the task list
* Prevent empty tasks from being added
* Save tasks to a text file
* Load previously saved tasks when the program starts
* Exit the program through the menu

## Requirements

* Python 3

## Project Files

* `tasktrack.py` — Contains the Python code for the TaskTrack program, including the menu, task loading, task saving, viewing tasks, and adding tasks.
* `tasks.txt` — Stores the user's tasks so they remain available after the program is closed.
* `.gitignore` — Tells Git which files or folders should not be tracked in the repository.

## Running the Program

Open Terminal or the integrated terminal in VS Code and navigate to the folder containing the TaskTrack project.

Run the following command:

```text
python3 tasktrack.py
```

This starts TaskTrack and displays the main menu in the terminal.

## Task Persistence

When TaskTrack starts, it loads existing tasks from `tasks.txt` into the program. When a new task is added, the updated task list is saved back to `tasks.txt`. Because the tasks are stored in this file, they remain available after the program is closed and can be loaded again the next time TaskTrack is started.

## Sample Interaction

```text
TaskTrack Menu
1. View tasks
2. Add task
3. Exit

Enter your choice: 2
Enter a new task: Finish CPS 310 assignment
Task added successfully.

TaskTrack Menu
1. View tasks
2. Add task
3. Exit

Enter your choice: 1

Tasks:
1. Finish CPS 310 assignment
```

## Current Limitations

* Tasks cannot currently be deleted.
* Existing tasks cannot currently be edited.
* Tasks cannot be marked as completed.
