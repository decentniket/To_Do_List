# To-Do List Application

## Overview
This project is a simple To-Do List web application that helps users organize and manage their daily tasks. It allows users to add tasks, mark them as completed, and keep track of their progress.

## Features
- Add new tasks
- Mark tasks as completed
- Visual indication of completed tasks
- Simple and clean interface
- Lightweight and easy to use

## How It Works
Tasks are displayed in a list. When a task is marked as completed, a CSS class called `done` is applied to the task item.

This class changes the appearance of the task:
- The text color becomes grey
- A line-through effect is added to indicate completion

Example CSS:

```css
#ulTasks li.done {
  color: #6c757d;
  text-decoration: line-through;
}
