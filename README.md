

# Java To-Do List Application

A console-based To-Do List application developed entirely in Java to manage daily tasks efficiently. This project demonstrates core Java programming, object-oriented design, and clean code practices, with a structure that can be extended as the application evolves.

## 🎯 Project Objectives

* Build a functional task management application using Java only.
* Apply object-oriented programming principles.
* Implement CRUD operations for tasks.
* Practice Java Collections and exception handling.
* Write modular, readable, and maintainable code.
* Prepare the codebase for future enhancements without unnecessary complexity.

## ✨ Features

* **Add Task:** Create new tasks.
* **View Tasks:** Display all available tasks.
* **Update Task:** Modify existing task details.
* **Delete Task:** Remove tasks by their identifiers.
* **Complete Task:** Mark tasks as completed.
* **Track Status:** Distinguish between pending and completed tasks.
* **Input Validation:** Handle invalid inputs and task identifiers.
* **Console Menu:** Interact with the application through a terminal.

*Feature availability depends on the current implementation.*

## 🛠️ Technology Stack

| Technology              | Purpose                                 |
| ----------------------- | --------------------------------------- |
| Java                    | Entire application                      |
| OOP                     | Organizing classes and responsibilities |
| ArrayList / Collections | Managing tasks in memory                |
| Exception Handling      | Handling errors safely                  |
| Git & GitHub            | Version control                         |

No frontend technologies or external frameworks are required.

## 🧠 Java Concepts Used

* Variables and data types
* Conditional statements and loops
* Methods and constructors
* Classes and objects
* Encapsulation
* Inheritance and polymorphism, where appropriate
* Abstraction, where appropriate
* Java Collections Framework
* Exception handling
* Modular programming

## 📂 Suggested Project Structure

```text
java-todo-list/
├── src/
│   ├── Main.java
│   ├── Task.java
│   └── TaskManager.java
├── README.md
├── .gitignore
└── LICENSE
```

### Class Responsibilities

* **Main.java:** Starts the application and handles the console menu.
* **Task.java:** Represents a task, including its ID, title, description, and completion status.
* **TaskManager.java:** Implements task creation, viewing, updating, deletion, and completion logic.

This is a suggested structure; adjust it to match your actual files.

## ⚙️ How to Run

### Prerequisites

* Java Development Kit (JDK) installed.
* A terminal or Java IDE.

Check your installation:

```bash
java -version
javac -version
```

Compile and run the application from the directory containing the Java files:

```bash
javac *.java
java Main
```

If your source files use packages, compile and run them using the appropriate package structure.

## 📈 Future Scalability Roadmap

The application will remain Java-only while its internal design improves.

### Phase 1 — Core Functionality

* Implement task CRUD operations.
* Add completion status.
* Handle invalid input and errors.

### Phase 2 — Better Task Management

* Add task priorities.
* Add due dates.
* Search, filter, and sort tasks.
* Generate unique task IDs.

### Phase 3 — Code Quality

* Separate task models from business logic.
* Use appropriate classes, interfaces, and enums.
* Add unit tests using JUnit.
* Improve validation and exception handling.

### Phase 4 — Persistent Storage

* Save and load tasks using Java file handling.
* Prevent data loss when the application closes.
* Optionally introduce JDBC and a database in a later version.

### Phase 5 — Advanced Java Development

* Improve data management and application reliability.
* Add logging and configuration.
* Explore multithreading only if a genuine requirement arises.

These are future possibilities, not claims about features already implemented.

## 🧪 Testing Checklist

* Add a task successfully.
* Display all tasks.
* Update an existing task.
* Delete an existing task.
* Mark a task as completed.
* Handle an empty task list.
* Handle invalid menu choices.
* Handle nonexistent task IDs.
* Verify task persistence after implementing file storage.

## 📌 Project Design Principles

* Keep each class responsible for a clear task.
* Avoid duplicating business logic.
* Use meaningful variable and method names.
* Validate inputs before modifying task data.
* Keep storage logic separate from task-management logic when the project grows.
* Add new features without making the existing code unnecessarily complicated.

## 👨‍💻 Author

**Ambi**

Computer Science and Engineering Student

**Focus:** Java Programming | Object-Oriented Programming | Data Structures and Algorithms

---

*Built with Java, focused on practical programming skills and continuous improvement.*
