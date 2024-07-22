# Todo App

A simple todo application using HTML, CSS, and JavaScript with local storage to persist tasks. The app allows users to add, edit, and delete tasks, with changes saved in the browser's local storage.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Code Overview](#code-overview)
- [Technologies Used](#technologies-used)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Features

- Add new tasks with a title, date, and description.
- Edit existing tasks.
- Delete tasks.
- Local storage to persist tasks between sessions.
- Simple and professional UI design.

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/todo-app.git
    ```
2. Navigate to the project directory:
    ```sh
    cd todo-app
    ```
3. Oepn `index.html` <strong>OR</strong> go [here](https://ash-taraghi.github.io/ToDo-LS-App/): 

## Usage

1. Open `index.html` or click the website link <strong>[here](https://ash-taraghi.github.io/ToDo-LS-App/)</strong> in your web browser.
2. Click "Add New Task" to open the task form.
3. Fill out the task details (Title, Date, Description) and click "Add Task".
4. To edit or delete a task, use the corresponding buttons next to each task.
5. To close the task form without saving, click the close button and confirm the action if there are unsaved changes.

## Code Overview

### HTML

The `index.html` file contains the structure of the Todo App, including the main elements such as the task form, buttons, and task container.

### CSS

The `styles.css` file contains the styles for the Todo App, including a professional business color scheme using CSS variables.

### JavaScript

The `script.js` file contains the logic for adding, editing, deleting tasks, and interacting with local storage.

#### Key Functions

- `addOrUpdateTask()`: Adds a new task or updates an existing task in the local storage and updates the UI.
- `updateTaskContainer()`: Renders the tasks from local storage to the task container.
- `deleteTask(buttonEl)`: Deletes a task from the local storage and updates the UI.
- `editTask(buttonEl)`: Loads the task data into the form for editing.
- `reset()`: Resets the form and hides it.

### Local Storage

The app uses the browser's local storage to persist tasks. Tasks are stored in a JSON format under the key `data`.

## Technologies Used

- HTML
- CSS
- JavaScript

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Inspired by various online todo app tutorials and examples.
- Icons by [Flaticon](https://www.flaticon.com/).

