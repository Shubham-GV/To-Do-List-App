# Todo List

A simple, responsive todo list app built with plain HTML, CSS and JavaScript (no frameworks, no dependencies). Everything lives in a single `index.html` file.

## Features

- Add new tasks (empty tasks are rejected)
- Mark tasks as completed with a checkbox
- Delete individual tasks
- Filter tasks: All, Active, Completed
- Live counter of tasks left
- "Clear completed" button
- Tasks are saved in your browser (localStorage), so they stay after a refresh
- Responsive layout for phone and desktop

## Project Structure

```
todo-list/
├── index.html   # page, styling and logic in one file
└── README.md
```

## Run Locally

Just open `index.html` in any browser. No build step needed.

## Deploy on GitHub Pages

1. Push this repo to GitHub.
2. Go to **Settings > Pages**.
3. Under **Branch**, select `main` and `/ (root)`, then save.
4. Your site will be live at `https://<your-username>.github.io/todo-list/`.

## Ideas to Extend

- Edit an existing task by double-clicking it
- Add due dates and priorities
- Drag and drop to reorder tasks
- Add a dark mode toggle
- Split the code into separate HTML, CSS and JS files

## License

MIT
