#  Java To-Do List Manager

This is a simple command-line **To-Do List Manager** written in Java. It allows users to add, view, remove, and mark tasks as done.

##  Features

- Add new tasks with descriptions
- View the list of tasks
- Remove tasks by number
- Mark tasks as completed
- Console-based menu system

##  How It Works

The application uses an `ArrayList` to store tasks, and a `Scanner` to handle user input. Each task is represented by a `Task` object (you'll need a separate `Task.java` class if not already included).

### Menu Options:
1. Add Task  
2. View Tasks  
3. Remove Task  
4. Mark Task as Done  
5. Exit

### Prerequisites
- Java JDK 8 or higher

### How to Run
1. Compile the code:
   ```bash
      javac ToDoListManager.java Task.java
2.  Run the code
    java ToDoListManager
