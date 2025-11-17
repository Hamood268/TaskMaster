# 📝 Task Manager CLI

A lightweight, interactive command-line Task Manager built with **Node.js**, using a local `tasks.json` file to store tasks.
Create, list, complete, and remove tasks with a simple menu-based interface.

---

## 🚀 Features

* **Add Tasks** with title, priority, and due date
* **List Tasks** with formatted output
* **Mark Tasks as Completed**
* **Remove Tasks** by ID
* **Persistent Storage** using a JSON file
* **Interactive CLI Menu**
* **Animated Exit Screen**

---

## 📦 Installation

```bash
git clone <repo-url>
cd <project-folder>
npm install
```

> No external packages required — only Node.js built-ins.

---

## ▶️ Usage

Run the Task Manager:

```bash
node index.js
```

You’ll see:

```
Task Manager Menu:
1. Add Task
2. List Tasks
3. Complete Task
4. Remove Task
5. Exit

Choose an option...
```

---

## 🧩 Task Structure

Each task is stored as an object inside `tasks.json`:

```json
{
  "id": 1731860954123,
  "title": "Example Task",
  "priority": "High",
  "dueDate": "2025-01-01",
  "completed": false
}
```

---

## 🔧 Available Actions

### ➕ Add Task

You will be prompted to enter:

* Title
* Priority (Low / Medium / High)
* Due Date (or leave blank → defaults to "Not Defined")

### 📋 List Tasks

Displays all tasks in a readable format, including status.

### ✅ Complete Task

Marks a task as completed using its ID.

### ❌ Remove Task

Deletes a task permanently using its ID.

### 📴 Exit

Triggers an animated 5-second exit countdown.

---

## 🛠️ How It Works

### TaskManager Class

Handles:

* Loading & saving tasks
* Adding, listing, completing, removing tasks
* Normalizes priority formatting
* Creates the JSON storage automatically

### CLI Interface

Implemented using:

* `readline`
* `process.stdin`
* `process.stdout`

Prompts the user with a menu loop until they choose **Exit**.

---

## 📜 License

MIT — feel free to modify and use in your own projects.

---

## Support me

My Socials:
- [GitHub](https://github.com/hamood268)
- [Discord: @ha268h](https://discord.com/users/804230882693087242)
- [X](https://x.com/Ha268h)

 [![PayPal](https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white)](https://paypal.me/Mohammed0268)

*Note*: This application lacks ton of functionality for an actual tasks manager/TODO app because it was made for learning and abandoned it early on,  thanks for checking it out hope you liked it!

*Developed with passion by Mohammed*