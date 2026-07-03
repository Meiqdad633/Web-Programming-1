# To-Do List Application

## Meiqdad Hassani
**Course:** Web Programming  1
**Assignment:** Event Handling and Event Delegation  
**Project:** To-Do List Application

---

## Project Description

This project is a simple To-Do List application created using HTML, CSS, and JavaScript. The purpose of the project is to demonstrate how JavaScript can manipulate the Document Object Model (DOM) and respond to user interactions using event handling and event delegation.

Users can add new tasks, edit existing tasks, remove tasks, and mark tasks as completed or incomplete. The application updates the page dynamically without refreshing the browser.

---

## Features

- Add a new task.
- Edit an existing task.
- Remove a task.
- Mark a task as complete or incomplete using a checkbox.
- Update the page dynamically using JavaScript.
- Use event delegation to handle user actions efficiently.

---

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6)

---

## How to Run the Project

1. Download the project file.
2. Save it as **todo.html**.
3. Open the file in any modern web browser such as:
   - Google Chrome
   - Microsoft Edge
   - Mozilla Firefox

No additional software or installation is required.

---

## Project Structure

The project contains three main sections:

### HTML
Creates the page layout including:
- Task input field
- Add Task button
- Task list
- Edit dialog

### CSS
Provides basic styling for:
- Layout
- Buttons
- Task list
- Completed tasks
- Edit dialog

### JavaScript
Implements the application logic including:
- Creating new tasks
- Editing tasks
- Removing tasks
- Completing tasks
- Event delegation

---

## Event Delegation

Instead of attaching separate event listeners to every button, one event listener is attached to the task list (`ul`). This listener detects which button or checkbox the user clicked and performs the appropriate action.

This approach makes the code more efficient and easier to maintain, especially when new tasks are added dynamically.

---

## Notes

- Empty tasks cannot be added.
- Edited tasks cannot be saved as empty text.
- Completed tasks are displayed with a strike-through effect.
- All updates happen immediately without reloading the page.

---

## References

Jeansoulin, R. (2018). *JavaScript and Open Data*. John Wiley & Sons.

MDN Web Docs. (2023). *Document Object Model (DOM).* https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model

Shute, Z. (2019). *Advanced JavaScript: Speed up Web Development with the Powerful Features and Benefits of JavaScript*. Packt Publishing.

---
**Author:** Meiqdad Hassani
