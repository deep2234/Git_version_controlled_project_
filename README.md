
# Git Version-Controlled DevOps Project

This project demonstrates Git best practices for a DevOps workflow, including proper branching strategy, pull request management, use of `.gitignore`, Git tags, and markdown documentation.

---

## 📁 Project Structure

```

├── assets/ # Images and other static assets
├── index.html # Main HTML page
├── style.css # CSS styles
├── script.js # JavaScript file
├── Dockerfile # Container setup
├── .gitignore # Files/folders to ignore
├── README.md # Project overview
└── TASKS.md # Steps & documentation

````

---

## 🛠️ Tools Used

- **Git** – Version control
- **GitHub** – Remote repository & Pull Requests
- **Markdown** – Documentation

---

## 🔁 Branching Strategy

- `main` – Production-ready stable branch
- `dev` – Integration branch for testing and reviewing features
- `feature/*` – Feature branches for individual tasks (e.g., `feature/readme-update`, `feature/add-docs`)

Each feature branch is merged into `dev` via Pull Requests. Once stable, `dev` is merged into `main`.


---

## 📌 Highlights

* ✅ Pull Request workflow with proper branch hierarchy
* ✅ Clean commit history
* ✅ Reusable Git strategy
* ✅ Proper documentation in Markdown
* ✅ Tag-based release versioning

---

## 📂 Documentation

| File         | Description                        |
| ------------ | ---------------------------------- |
| `README.md`  | Project overview and Git structure |
| `TASKS.md`   | Step-by-step record of tasks       |
| `.gitignore` | Defines untracked files            |

---

