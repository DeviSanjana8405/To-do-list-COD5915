# To-do-list-COD5915
# To-Do List Web Application Documentation
## Introduction
Welcome to the To-Do List Web Application documentation! This project is a simple yet powerful tool for managing tasks and staying organized. Built using HTML, CSS, and JavaScript, it offers a user-friendly interface for adding, editing, and deleting tasks. This documentation aims to provide detailed explanations of the code, along with images illustrating the program's execution and user interactions.
## Features
1. **Add Tasks**: Users can easily add new tasks to the list by typing in the task description and pressing Enter or clicking the "Add" button.
2. **Edit Tasks**: Tasks can be edited inline by clicking on them, modifying the text, and pressing Enter to save changes.
3. **Delete Tasks**: Unwanted or completed tasks can be removed from the list by clicking the "Delete" button next to each task.
4. **Mark Tasks as Completed**: Users can mark tasks as completed by clicking the checkbox next to each task.
5. **Local Storage**: The application utilizes browser's local storage to persist tasks even after page refresh.
## Implementation Overview
The To-Do List Web Application is implemented using three primary technologies:
- **HTML (Hypertext Markup Language)**: Responsible for the structure and content of the web page.
- **CSS (Cascading Style Sheets)**: Handles the presentation and styling of the web page, ensuring a visually appealing and user-friendly interface.
- **JavaScript**: Provides the functionality and interactivity of the application, including adding, editing, and deleting tasks, as well as managing local storage.
## Code Explanation
### HTML Structure
The HTML structure of the To-Do List Web Application consists of the following components:
- `<header>`: Contains the application title.
- `<input>`: Text input field for adding new tasks.
- `<ul>`: Unordered list element to display the list of tasks.
- `<li>`: List items representing individual tasks, each containing a checkbox, task description, and delete button.
### CSS Styling
The CSS stylesheet defines the visual appearance of the application, including layout, colors, fonts, and animations. Key CSS styles include:
- Styling the header, input field, task list, and individual tasks.
- Applying hover effects and transitions for interactive elements.
- Responsive design to ensure proper display on different screen sizes.
### JavaScript Functionality
The JavaScript code provides the functionality and interactivity of the application. Key JavaScript functions include:
- **`addTask()`:** Adds a new task to the list when the user presses Enter or clicks the "Add" button.
- **`editTask()`:** Allows the user to edit a task by clicking on it, modifying the text, and pressing Enter to save changes.
- **`deleteTask()`:** Deletes a task from the list when the user clicks the delete button.
- **`toggleTaskStatus()`:** Toggles the completion status of a task when the user clicks the checkbox.
- **`saveTasksToLocalStorage()`:** Saves the current list of tasks to the browser's local storage.
- **`loadTasksFromLocalStorage()`:** Retrieves the list of tasks from local storage when the page is loaded.
### Local Storage
The application utilizes browser's local storage to persist tasks even after page refresh. This ensures that users can access their to-do list across different sessions.
## User Interactions
### Adding a Task
![Adding a Task](add_task.gif)
### Editing a Task
![Editing a Task](edit_task.gif)
### Deleting a Task
![Deleting a Task](delete_task.gif)
### Marking a Task as Completed
![Marking a Task as Completed](mark_task_completed.gif)
## Conclusion
The To-Do List Web Application offers a simple yet effective solution for managing tasks and staying organized. By leveraging HTML, CSS, and JavaScript, it provides users with a user-friendly interface and essential task management features. Whether you're a beginner looking to enhance your coding skills or an experienced developer seeking a practical project to showcase your abilities, this project offers an exciting opportunity to explore web development concepts and create a valuable tool for personal or professional use.
