# Todo List Application

A feature-rich, responsive todo list application with local storage functionality built with vanilla HTML, CSS, and JavaScript.

## Features

✨ **Core Features:**
- ➕ Add new tasks with instant feedback
- ✅ Mark tasks as completed
- 🗑️ Delete individual tasks
- 💾 Persistent storage using browser's Local Storage
- 🔍 Filter tasks by status (All, Active, Completed)
- 📊 Task counter showing remaining active tasks
- 🧹 Clear all completed tasks at once

🎨 **UI/UX:**
- Beautiful gradient background
- Responsive design (works on desktop, tablet, mobile)
- Smooth animations and transitions
- Accessible interface with keyboard support
- Empty state messages
- Visual feedback for completed tasks

## Files

- **index.html** - Main HTML structure
- **styles.css** - Complete styling and responsive design
- **app.js** - Application logic with local storage management
- **README.md** - This file

## How to Use

1. **Open the Application:**
   - Simply open `index.html` in any modern web browser

2. **Add a Task:**
   - Type your task in the input field
   - Click "Add Task" button or press Enter
   - Task will appear at the top of the list

3. **Complete a Task:**
   - Click the checkbox next to a task to mark it as complete
   - Completed tasks will be visually distinguished with strikethrough text

4. **Delete a Task:**
   - Click the "Delete" button on any task
   - Task will be removed from the list

5. **Filter Tasks:**
   - Click "All" to see all tasks
   - Click "Active" to see only incomplete tasks
   - Click "Completed" to see only finished tasks

6. **Clear Completed Tasks:**
   - Click "Clear Completed" button to remove all finished tasks at once
   - Confirmation dialog will appear

## Local Storage

All tasks are automatically saved to your browser's local storage. This means:
- ✓ Tasks persist after closing the browser
- ✓ Tasks are stored locally on your device
- ✓ No server or internet connection needed
- ✓ Storage is cleared only when you clear browser data or use the app's delete functions

**Storage Key:** `botberry_todos`

Each task stores:
- Unique ID (timestamp-based)
- Task text
- Completion status
- Creation date

## Technical Details

### Technologies Used
- **HTML5** - Semantic markup
- **CSS3** - Flexbox layout, gradients, animations
- **Vanilla JavaScript** - No frameworks or dependencies

### Browser Compatibility
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Opera (latest)

### Local Storage Capacity
- Typically 5-10MB per domain (varies by browser)
- This app uses minimal storage (~1KB per task on average)

## Future Enhancements

Potential features for future versions:
- 📅 Due dates for tasks
- 🏷️ Categories and tags
- 🎨 Theme customization (dark mode)
- 📤 Export/Import tasks
- 🔔 Notifications and reminders
- 🌙 Dark mode toggle
- 📱 Progressive Web App (PWA) support
- 🔄 Cloud sync capability

## License

This project is open source and available for personal and educational use.

## Author

Created with ❤️ for the Botberry Platform

---

**Enjoy organizing your tasks! 🎯**
