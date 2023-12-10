This simple To-Do List Manager is a console-based Python application that allows users to manage their tasks efficiently. Users can view tasks, add new tasks, update existing tasks, delete tasks, and save their task list to a file.

**Features**:

1. Show Tasks: Display all the tasks in the to-do list.
2. Add Tasks: Add a new task to the to-do list.
3. Update Tasks: Modify an existing task in the to-do list.
4. Delete Tasks: Remove a task from the to-do list.
5. Save and Exit: Save the current to-do list to a file and exit the application.

**How to Use**:

1. Run the script in a Python environment.
2. The program will load tasks from the "todo_list.txt" file (if it exists).
3. Choose options from the menu to manage your to-do list.
4. Save your tasks and exit when done.

**Example:**


$ python todo_manager.py

********** To-Do List *********
1. Show Tasks
2. Add Tasks
3. Update Tasks
4. Delete tasks
5. Save and Exit

Enter Your Choice: 2
Enter the task to add: Complete project report
Task Added Successfully.

********** To-Do List *********
1. Complete project report

Enter Your Choice: 3
Enter the task index to update: 1
Enter the updated task: Submit project report
Task Updated Successfully.

...

Enter Your Choice: 5
Tasks saved. Exiting..

**File Persistence:**

The to-do list is saved to the "todo_list.txt" file, ensuring that your tasks persist between sessions.

**Note:**

The program handles invalid inputs gracefully and provides appropriate messages.
The task list is maintained in memory during the session.
Feel free to use, modify, and share this simple To-Do List Manager! If you encounter any issues or have suggestions for improvement, please open an issue or submit a pull request.

Happy task managing!
