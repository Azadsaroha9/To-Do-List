# To-Do List Application

This is a simple To-Do List application built using Python's Tkinter library. It allows users to add and delete tasks, with the tasks being saved in a file called `data.txt`.

## Features

- Add tasks to the to-do list.
- Delete tasks from the to-do list.
- Tasks are saved to a file and loaded upon restarting the application.

## Requirements

- Python 3.x

## Installation

1. **Clone the repository** (or simply download the `todo.py` file):
    ```sh
    git clone https://github.com/your-Azadsaroha9/To-Do-List.git
    ```

2. **Navigate to the project directory**:
    ```sh
    cd To-Do-List
    ```

## Usage

1. **Run the application**:
    ```sh
    python todo.py
    ```

2. **Add a task**:
    - Type the task into the text box under the "Add Task" label.
    - Click the "Add" button to add the task to the list.

3. **Delete a task**:
    - Select the task from the list.
    - Click the "Delete" button to remove the selected task from the list.

## File Structure

- `todo.py`: The main application file containing the Tkinter GUI code.
- `data.txt`: The file where tasks are saved. This file is automatically created if it does not exist.

## Code Overview

- The `Todo` class handles the main functionality of the application:
  - **`__init__`**: Sets up the GUI components.
  - **`add`**: Adds a new task to the list and saves it to `data.txt`.
  - **`delete`**: Deletes the selected task from the list and updates `data.txt`.
  - **`load_tasks`**: Loads tasks from `data.txt` into the listbox when the application starts.
  - **`update_file`**: Updates `data.txt` after a task is deleted.

- The `main` function initializes the Tkinter root window and starts the application's main loop.

## Contributing

Feel free to fork this repository and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.


