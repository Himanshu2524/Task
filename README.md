This is a simple React + TypeScript Todo App that allows users to manage their daily tasks with the following features:

✅ Core Features:
Add New Tasks

Users can enter a new task and add it to the list.

Each task is stored with a unique ID and text content.

Edit Existing Tasks

Each task has an edit icon (✏️).

Clicking the edit button turns the task into an input field.

After making changes, pressing Enter updates the task in the list.

Delete Tasks

Each task has a delete icon (🗑️).

Clicking it will remove that task from the list permanently.

Mark Tasks as Done

Each task has a checkbox.

Checking the box can be used to mark the task as completed (e.g., with a strikethrough or style change).

🧱 Tech Stack:
React (Function Components & Hooks)

TypeScript (for type safety)

Tailwind CSS (for styling)

React Icons (for UI icons like edit/delete)

🧠 How It Works (Behind the Scenes):
useState is used to manage the list of todos (todos) and local editing state (editthis, useedit).

Each SingleTask component receives the todo and update function as props.

When editing or deleting, setTodos is called to update the main task list.

🎯 Possible Improvements (Optional):
Add task filtering (All / Completed / Active)

Save todos to localStorage

Add due dates or priorities

Dark mode toggle
