# taskflow
analysis of progress
# TaskFlow

A lightweight task manager built as a single `index.html` file.

## Overview

`index.html` contains a complete todo application implemented with:
- semantic HTML layout
- inline CSS for styling and responsive design
- vanilla JavaScript for task management, theme toggling, filters, and persistence

## Features

- Add tasks using the input field and Add button
- Mark tasks complete or incomplete
- Edit existing task text inline
- Delete individual tasks
- Filter tasks by All, Pending, or Completed
- View task counts for total, pending, and completed
- Progress bar updates dynamically
- Clear completed tasks with one button
- Dark mode / light mode toggle
- Saved tasks and theme persist in `localStorage`

## Usage

1. Open `index.html` in any modern browser.
2. Type a task into the input field and press Enter or click **Add Task**.
3. Use the filter buttons to view all, pending, or completed tasks.
4. Click the moon/sun button to switch between dark and light mode.
5. Click the checkbox button on a task to toggle completion.
6. Click the pencil icon to edit a task, or the trash icon to delete it.
7. Click **Clear Completed** to remove all completed tasks.

## Notes

- No build tools or server are required.
- The app is fully contained in one HTML file with inline styling and scripting.
- Data is stored locally in the browser, so tasks will remain after refresh.

## File

- `index.html` — main application file
