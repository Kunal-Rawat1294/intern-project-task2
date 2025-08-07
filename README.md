# To-Do List App

This repository contains a simple, interactive To-Do List web application, built using HTML, CSS, and JavaScript. The app provides an intuitive interface for managing daily tasks, supporting features like task creation, deletion, completion marking, filtering, and clearing completed tasks.

---

## Features

- **Add Tasks:** Quickly add new tasks using the input field and "Add" button (or by pressing Enter).
- **View Tasks:** All tasks are displayed in a clean, scrollable list.
- **Mark as Completed:** Tick the checkbox next to a task to mark it as completed; completed tasks are styled with a strikethrough.
- **Delete Tasks:** Remove any unwanted task using the trash icon.
- **Filter Tasks:** View all tasks, only active tasks, or only completed tasks using the filter buttons.
- **Clear Completed:** Remove all completed tasks at once with the "Clear Completed" button.
- **Task Counter:** Displays the number of active (incomplete) tasks remaining.

---

## File Structure

```
intern-project-task2/
├── intern-task2/
│   ├── index.html      # Main HTML file defining the app structure.
│   ├── styles.css      # Application styling for layout and visuals.
│   ├── script.js       # JavaScript logic for app functionality.
├── README.md           # Project overview and usage instructions.
```

---

## Usage

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Kunal-Rawat1294/intern-project-task2.git
   ```

2. **Open the App:**
   - Navigate to the `intern-task2` folder.
   - Open `index.html` in your web browser.

3. **Interacting with the App:**
   - Enter a task and click "Add" or press Enter.
   - Use the filter buttons to toggle between all, active, and completed tasks.
   - Click the checkbox to mark a task as completed.
   - Use the trash icon to delete a task.
   - Click "Clear Completed" to remove all completed tasks.

---

## Customization & Styling

- The app uses a modern, responsive design with pastel gradients and interactive elements.
- Font Awesome icons are included for task deletion.
- All styling can be modified via `styles.css`.

---

## How it Works

- **State Management:** Tasks are stored in a JavaScript array, with each task represented as an object (`{id, text, completed}`).
- **Dynamic Rendering:** The task list updates dynamically as you add, delete, complete, or filter tasks.
- **Event Handling:** User interactions (clicks, keypresses, etc.) are managed using standard DOM event listeners.

---

## License

This project is open-source and available under the MIT License.

---

## Author

Made by [Kunal Rawat](https://github.com/Kunal-Rawat1294)
