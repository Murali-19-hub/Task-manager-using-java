# Task Manager

A simple Java-based task manager that allows users to add, edit, delete, and view tasks. The program utilizes a `HashMap` to store tasks, each associated with a unique ID. The user interacts with the program through a command-line interface.

## Features

- **Add Task**: Add a new task with a description.
- **Edit Task**: Edit the description of an existing task by providing the task ID.
- **Delete Task**: Delete a task by its ID.
- **View Tasks**: View all current tasks with their respective IDs.
- **Exit**: Exit the program.

## Requirements

- **Java 8** or higher.
  
## How to Run

1. **Install Java**:
   Make sure that Java is installed on your system. You can verify this by running the following command:
   ```bash
   java -version
If Java is not installed, you can download and install it from the official Java website.

Save the Code: Save the code into a file named TaskManager.java.

Compile the Code: Open a terminal and navigate to the directory where you saved the TaskManager.java file. Then, compile the code using:

bash
Copy
javac TaskManager.java
Run the Program: Once compiled, run the program with the following command:

bash
Copy
java TaskManager
This will start the task manager application, and you can interact with it through the terminal.

Sample Usage
mathematica
Copy
Task Manager Menu:
1. Add Task
2. Edit Task
3. Delete Task
4. View Tasks
5. Exit
Enter your choice: 1
Enter task description: Finish homework
Task added with ID 1: Finish homework

Task Manager Menu:
1. Add Task
2. Edit Task
3. Delete Task
4. View Tasks
5. Exit
Enter your choice: 4
Current tasks:
ID 1: Finish homework
Menu Options
1. Add Task: You will be prompted to enter a task description. The task will be assigned a unique ID.

2. Edit Task: Enter the task ID you want to edit and provide a new description.

3. Delete Task: Enter the task ID you want to delete.

4. View Tasks: Displays all current tasks and their IDs.

5. Exit: Exits the program.

Example Code Walkthrough
The code consists of a TaskManager class that manages tasks in a HashMap. Each task is identified by a unique integer ID, which is automatically incremented each time a new task is added.

Main Components:
TaskManager Constructor: Initializes the tasks HashMap and the taskCounter.

addTask(): Adds a task to the tasks map with a unique ID.

editTask(): Allows editing of an existing task by its ID.

deleteTask(): Deletes a task by its ID.

viewTasks(): Displays all tasks with their IDs.

Main Method:
The main method provides a menu-driven interface, prompting the user for input to choose the desired action (add, edit, delete, view, or exit).

License
This project is open-source and free to use. You can modify, distribute, or use it in your own projects.

