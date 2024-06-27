# To-Do List Application with GTKmm and Splay Tree

This is a simple graphical to-do list application built using GTKmm for the GUI and a splay tree for efficient task management. The application allows users to add, mark as done, remove, and display tasks with priority levels.

## Features

- **Add Task**: Add a new task with a description and priority level.
- **Mark Task as Done**: Mark a specific task as completed.
- **Remove Task**: Remove a task from the list.
- **Display Tasks**: Display all tasks with their statuses and priorities.
- **Most Prioritized Task**: Display the task with the highest priority.

## Project Structure

- **main.cpp**: Entry point of the application.
- **task.h/task.cpp**: Defines the `Task` class representing individual tasks.
- **splay_tree.h/splay_tree.cpp**: Implements a generic splay tree data structure.
- **todolist.h/todolist.cpp**: Manages tasks using the splay tree.
- **todo_list_gui.h/todo_list_gui.cpp**: Implements the GTKmm-based GUI for the to-do list.

## Installation

### Prerequisites

- C++ compiler (e.g., `g++`)
- GTKmm 3.0
