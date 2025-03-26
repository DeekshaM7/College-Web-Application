# College-Web-Application

# TaskMaster: A React-based Task Management App

TaskMaster is a dynamic and responsive task management application built using React. It provides users with a feature-rich dashboard for managing tasks, toggling between light and dark themes, and navigating between multiple sections like tasks, dashboard, and user profile.

---

## Features

### Theme Switching (Light/Dark Mode)
- Toggle between light and dark themes for improved user experience and accessibility.

### Tabbed Navigation
- Navigate seamlessly between three main sections:
  - **Tasks:** Manage your to-do list.
  - **Dashboard:** View statistical insights (feature in progress).
  - **Profile:** Manage and update user details (feature in progress).

### Task Management
- Add new tasks using a simple form.
- Toggle task completion status (mark tasks as done/undone).
- Delete tasks from the list.
- Tasks are displayed in a visually organized, responsive list.

### Dynamic User Interface
- React's state management dynamically updates components for a smooth user experience.
- Conditional rendering displays content based on the active tab.

### User Profile
- Displays a mock user profile with a name, role, and avatar.
- Includes the ability to update user details (implementation pending).

### Reusability and Clean Code Structure
- Modular components (`Header`, `Navigation`, `TaskManager`, `TaskItem`, `Footer`) ensure easy extensibility and maintenance.

---

## Core Components

### Dashboard (Main Component)
- Manages the application's state (e.g., tasks, theme, active tab, user profile).
- Coordinates interactions between child components.

### TaskManager
- Provides a form to add new tasks and displays a list of current tasks.
- Includes logic for task addition, deletion, and status toggling.

### Header
- Displays the app's title (`TaskMaster`), a theme toggle button, and user profile details.

### Navigation
- Allows navigation between the app's three main sections: tasks, dashboard, and profile.

### TaskItem
- Represents an individual task in the task list with options to mark it completed or delete it.

---

## Styling
- Utilizes dynamic class names for theme-based styling to ensure a consistent and responsive user experience.

---

## How to Run the Project

$ git clone https://github.com/yourusername/College-Web-Application

$ cd college-signup-portal

Install Dependencies

$ npm install

Run the Development Server

$ npm run dev

Visit http://localhost:3000.


## Future Improvements

1. Add persistent storage using localStorage or a database.

2. Enhance the Dashboard with task statistics and graphs.

3. Complete the implementation of the Profile section for user updates.

4. Introduce advanced features like task categorization and reminders.

## License
This project is licensed under the MIT License.

## Contributing
Contributions are welcome! Feel free to submit a pull request or open an issue to report bugs or suggest features.
