# Task List Web Application

This is a simple task list web application where users can add, edit, complete, and delete tasks. The application uses HTML, CSS, and JavaScript for functionality and styling.

## Features

- **Add Task**: Users can add new tasks using the input field in the header.
- **Edit Task**: Tasks can be edited by clicking the "Edit" button associated with each task. Clicking "Save" will save the edited task.
- **Complete Task**: Tasks can be marked as completed by checking the checkbox next to each task.
- **Delete Task**: Tasks can be deleted using the "Delete" button associated with each task.
- **Persistence**: Tasks are stored locally using `localStorage`, so they persist between sessions.

## Technologies Used

- **HTML**: Provides the structure and semantic elements.
- **CSS**: Styles the application for a clean and modern interface.
- **JavaScript**: Implements dynamic behavior, including adding, editing, completing, and deleting tasks.

## How to Use

1. **Adding a Task**:
   - Type your task into the input field in the header.
   - Click the "Add task" button or press Enter to add the task to the list.

2. **Editing a Task**:
   - Click the "Edit" button next to the task you want to edit.
   - Modify the task text in the input field that appears.
   - Click "Save" to save your changes or click outside the input field to cancel.

3. **Completing a Task**:
   - Check the checkbox next to the task you want to mark as completed.
   - Completed tasks move to the "Completed Tasks" section automatically.

4. **Deleting a Task**:
   - Click the "Delete" button next to the task you want to delete.
   - The task will be removed from the list permanently.

## Installation

- Clone the repository:
  ```bash
  git clone https://github.com/hilpresent/task-list.git
  ```

- Open `index.html` in your web browser.

## Customization

- **Colors**: Customize the color scheme by modifying CSS variables in `todo_style.css` (`:root` section).
- **Fonts**: Adjust fonts by modifying or linking additional fonts in the HTML file (`<link rel="stylesheet" href="https://code.cdn.mozilla.net/fonts/fira.css">`).

## Contributing

Contributions are welcome! Feel free to fork the repository and submit pull requests for new features, improvements, or bug fixes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
