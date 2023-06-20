DATA ANALYTICS (PYTHON MINI PROJECT ON TASK TRACKER)
TASK TRACKER
This code is a straightforward Python task tracking application. With a CSV file serving as the data storage medium, users can add tasks, examine already-existing tasks, modify tasks, and delete tasks. Here is a description of how the code functions:
1) The csv, os, and datetime modules are first imported into the code. Working with dates and times, connecting with the operating system, and processing CSV files are all accomplished with these modules.
2) The constant variable TASKS_FILE is set to the name of the CSV file that contains the tasks.
3) The main_menu() function is designed to show the application's main menu and ask the user to make a selection. Next, the user's selection is returned.
4) The user can enter a task's name, description, and due date using the add_task() function. The csv.writer object is then used to append the task details to the CSV file.
5) Using the csv.reader object, the view_tasks() function reads the CSV file and formats the stored tasks for display. Column headers are printed with the task specifics.
6) The function edit_task() reads the tasks from the CSV file, displays them along with the respective IDs, and asks the user to input the ID of the task they want to edit. The task's new details, which are updated in the CSV file, can then be provided by the user.
7)The delete_task() function extracts the tasks from the CSV file, shows them together with the respective IDs, and asks the user to input the ID of the task they want to delete. The chosen item is taken off the list, and the task list as it has been amended is then written back to the CSV file.
8)Until the user decides to stop it, the main programme loop continues to operate. It repeatedly shows the main menu, evaluates the user's selection, and then invokes the relevant function in accordance with the selection.


A task tracker application
A task tracker application is a program that helps users manage and track their tasks or to-do lists. It provides features to add, view, edit, and delete tasks, allowing users to organize their work and stay on top of their responsibilities. Here's an explanation of the main components and benefits of a task tracker application in Python:

Components of a Task Tracker Application:
1. Task Storage: A task tracker application typically uses a data storage mechanism to store task information. This can be a database, a file (such as a CSV file, as in the provided code), or an in-memory data structure.
2. Task Operations: The application allows users to perform common operations on tasks, such as adding, viewing, editing, and deleting tasks. These operations are typically implemented as functions or methods within the application.

Benefits of a Task Tracker Application:
1. Organization: A task tracker helps users stay organized by providing a centralized location to manage and track their tasks. It allows users to prioritize tasks, set due dates, and maintain a structured workflow.
2. Task Visibility: With a task tracker, users can easily view and access their tasks in one place. This improves visibility and reduces the chances of forgetting or overlooking important tasks.
3. Progress Tracking: Task tracker applications often include features to track task progress, such as marking tasks as completed, adding comments or notes, or setting task statuses. This helps users monitor their progress and identify areas that need attention.
4. Data Persistence: Task tracker applications store task data persistently, allowing users to access their tasks across multiple sessions or devices. This ensures that tasks and their details are not lost and can be retrieved whenever needed.
5. Customization and Flexibility: Depending on the application, users may have the option to customize task attributes, create task categories or tags, set reminders, and apply filters or sorting options. This flexibility enables users to tailor the task tracker to their specific needs and preferences.


