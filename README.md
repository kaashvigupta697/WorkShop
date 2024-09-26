Task App
Overview
This is a simple Task App that allows users to add tasks to a list. It features a basic HTML structure, CSS for styling (if needed), and JavaScript for interactivity. Users can enter a task name and submit it to see it displayed in a table.

Features
Add tasks to a list
Dynamically updates the list without page refresh
Simple and user-friendly interface
Technologies Used
HTML
CSS (optional, not included in this code)
JavaScript
Getting Started
To run the Task App locally, follow these steps:

Clone the Repository (if applicable):

bash
Copy code
git clone [repository-url]
Open the HTML file:

Locate the index.html file (or whatever you name it) in your file explorer.
Open it with a web browser (e.g., Chrome, Firefox).
Usage:

Enter a task name in the input field.
Click the "Add Task" button to add the task to the list.
The task will appear in the table below.
Code Explanation
HTML Structure
Table: Displays the list of tasks with a header for "Task Name".
Form: Contains an input field for entering new tasks and a button to submit the form.
JavaScript Functionality
An event listener is added to the form to handle the submit event.
The default form submission is prevented to keep the page from reloading.
The value from the input field is retrieved and added to a new table row.
The new task is appended to the task list in the table.
Future Improvements
Add functionality to remove tasks.
Include validation to prevent adding empty tasks.
Implement task completion status (e.g., a checkbox).
Style the application using CSS for a better user experience.
