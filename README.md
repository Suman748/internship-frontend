# Internship Frontend

React + Vite frontend for the Sketchverse Task Management application.

## Features

- Responsive task list (1 column on mobile, 2 columns on desktop)
- Add, delete and update the status of tasks
- Search by title and filter by status
- Tasks saved in the browser (localStorage)

## Run locally

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

Build for production:

```bash
npm run build
```

## Project structure

```
src/
  App.jsx          # page layout, search and filter state
  components/      # TaskList.jsx, TaskForm.jsx, Filters.jsx
  hooks/           # useTasks.js
  data/            # mockTasks.js
```
