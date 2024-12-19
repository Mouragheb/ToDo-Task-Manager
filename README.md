# TODO TASKS APP HTML/CSS/JS/LOCAL STORAGE

A Pen created on CodePen.io. Original URL: [https://codepen.io/Mouragheb/pen/dPbMaep](https://codepen.io/Mouragheb/pen/dPbMaep).

Description of the App
This is a Todo Tasks App, a simple web application designed to help users manage tasks effectively. It allows users to:
1. Add Tasks: Users can provide a task title, set a date, and add a description.
2. Edit Tasks: Existing tasks can be updated with new details.
3. Delete Tasks: Tasks can be removed from the list.
4. Save Tasks Persistently: Tasks are stored in the browser’s localStorage, ensuring that they remain available even after refreshing the page or reopening the app.
5. Manage Tasks via a User-Friendly Interface:
• The app includes a clean form to input task details.
• Tasks are displayed in a structured format, with options to edit or delete each task.
Features
• Dynamic UI: The app dynamically updates the task list based on user actions (e.g., adding or deleting a task).
• Form Validation: Ensures users cannot add tasks without a title.
• Modal Dialog: Prompts the user to confirm when closing the form with unsaved changes.
• Interactive Design: Buttons and layout are styled for usability and aesthetics.
Languages and Techniques Used
1. HTML:
• Structure: Provides the basic framework for the app, including the form, task list container, and modal dialog.
• Accessibility: ARIA attributes and semantic elements are used for better usability.
2. CSS:
• Custom Variables: For reusable color schemes (e.g., –white, –light-blue, –pink).
• Responsive Design: Media queries ensure the app is optimized for different screen sizes.
• Styling: Adds modern aesthetics with gradients, rounded borders, and consistent spacing.
• Animations: Subtle hover effects on buttons improve interactivity.
3. JavaScript:
• Dynamic Interactions: Updates the DOM to reflect changes (e.g., adding, editing, or deleting tasks).
• localStorage: Persists tasks so they are retained across sessions.
• Event Handling: Listens for user actions like form submission, button clicks, and modal interactions.
• Validation: Prevents users from submitting incomplete tasks.
4. Web APIs:
• localStorage: Stores and retrieves task data.
• Dialog: Implements the modal dialog box for confirming unsaved changes.
5. Best Practices:
• Separation of Concerns: The code is structured to keep HTML, CSS, and JavaScript separate, making it modular and maintainable.
• Functions for Reusability: Functions like addOrUpdateTask and updateTaskContainer simplify and organize the logic.
How It Works
1. Adding a Task:
• When the “Add New Task” button is clicked, the form is displayed.
• The user fills in the details and submits the form.
• The task data is saved in localStorage and displayed in the task list.
2. Editing a Task:
• Clicking “Edit” on a task loads its details into the form.
• The user updates the information and saves changes.
3. Deleting a Task:
• Clicking “Delete” removes the task from the UI and localStorage.
4. Handling Unsaved Changes:
• If the user attempts to close the form with unsaved changes, a dialog prompts them to confirm.
Conclusion
In this Project I created a lightweight, functional, and visually appealing task management app using fundamental web development tools: HTML, CSS, JavaScript, and Web APIs. This is an excellent example of building a small-scale, interactive web application.
