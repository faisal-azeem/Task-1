# DecodeLabs To-Do Engine

A simple and efficient Command Line Interface (CLI) To-Do List application built for **Project 1** of the **DecodeLabs Industrial Training Kit (Batch 2026)**. This app uses clean text menus, distinct ANSI terminal colors, and file persistence.

---

## 🚀 Features

* **View Tasks:** Displays your current items in a clean, color-coded tabular view showing Task IDs, Statuses, and Timestamps.
* **Add New Task:** Prompts you for a title and instantly logs it with an auto-incrementing ID.
* **Mark Task as Done:** Updates a chosen task's status from `Pending` to `Done` instantly.
* **Delete Task:** Flushes a task from your list and dynamically re-indexes the remaining IDs sequentially to keep your database structured.
* **Data Persistence:** Automatically tracks your state and saves everything to a local `tasks.json` file so your tasks are saved when you exit.

---

## 📂 File Structure

* `todo_app.py` — The core Python engine containing the user navigation menus and data modification logic.
* `tasks.json` — The storage file where your items are saved as a structured JSON collection.

---

## 🛠️ How to Run

### 1. Execute the Script
Open your terminal, navigate to your project directory, and run:
```bash
python todo_app.py
