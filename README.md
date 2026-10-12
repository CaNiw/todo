# React Todo List

A beginner-friendly todo app built with React and Vite.

## Features

- Add tasks
- Mark tasks as complete or active
- Delete individual tasks
- Filter by all, active, and completed
- Clear completed tasks
- Persist tasks in browser `localStorage`
- Responsive layout

## Requirements

- Node.js (LTS recommended)
- npm

## Run locally

```bash
npm install
npm run dev
```

Open the local URL printed by Vite in your terminal.

## Production build

```bash
npm run build
npm run preview
```

## Project structure

```text
react-todo/
├── index.html
├── package.json
├── README.md
├── .gitignore
└── src/
    ├── main.jsx
    ├── App.jsx
    ├── App.css
    └── components/
        ├── TodoForm.jsx
        ├── TodoList.jsx
        └── TodoItem.jsx
```

Tasks are saved in the current browser and website origin. They do not sync between devices.
