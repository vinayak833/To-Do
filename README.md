# To-Do List Web Application

A simple and responsive **To-Do List** web application built using **HTML, CSS, and JavaScript**. Users can add tasks, mark them as completed, delete tasks, and save their task list using the browser's Local Storage.

---

## Features

- Add new tasks
- Mark tasks as completed
- Delete tasks
- Automatically saves tasks using Local Storage
- Tasks remain after refreshing the page
- Responsive and clean user interface

---

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6)
- Local Storage API

---

## Project Structure

```text
To-Do-List/
│── index.html
│── style.css
│── script.js
```

---

## How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/your-username/todo-list.git
```

2. Open the project folder.

3. Open **index.html** in your preferred web browser.

No additional installation or setup is required.

---

## How to Use

1. Enter a task in the input field.
2. Click the **Add** button.
3. Click on a task to mark it as completed.
4. Click the **×** button to remove a task.
5. Tasks are automatically saved in your browser.

---

## Functionality

### `addTask()`

- Adds a new task to the list.
- Prevents empty tasks from being added.
- Creates a delete (`×`) button for each task.
- Saves the updated list to Local Storage.

### `saveData()`

- Stores the current task list in Local Storage.

### `showTask()`

- Retrieves saved tasks from Local Storage when the page loads.

### Event Listener

- Toggles task completion status.
- Deletes tasks.
- Updates Local Storage after every change.

---

## Local Storage

The application stores tasks using the browser's **Local Storage**.

```javascript
localStorage.setItem("data", listContainer.innerHTML);
```

Saved tasks are automatically restored whenever the page is reopened.
### JavaScript

The JavaScript file manages all application functionality, including:

- Creating new tasks
- Validating user input
- Marking tasks as completed
- Removing tasks
- Saving task data
- Loading stored tasks
- Handling click events efficiently
  
## Learning Outcomes

This project demonstrates the use of:

- DOM Manipulation
- Event Handling
- Dynamic HTML Element Creation
- CSS Styling and Layout
- Local Storage API
- JavaScript Functions
- Event Delegation
