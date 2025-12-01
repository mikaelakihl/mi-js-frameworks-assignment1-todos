# Todo Application

This project was developed as a school project at Medieinstitutet. A client-side Todo Application built with React and TypeScript. It allows users to manage tasks, track their progress, and categorize them by emotion.

The core objective of this assignment was to work with React components and state management, specifically implementing features like "Lifting State Up" and CRUD operations. This was the first experience creating an application with React, with the ambition of creating a smoother and more intuitive task management experience.

State regarding todos is persisted to `localStorage`, ensuring that user tasks survive page reloads. The main focus lies in state management, component structure, and user interface design.

## 📋 Project overview

The app manages a list of tasks and handles user interactions locally. It consists of:

- **Todo List** – Active tasks with filtering and sorting options.
- **Finished Todos** – Completed tasks history.
- **Todo Form** – Interface to add new tasks with emotion categories.

Users can:

- Add new todos with an associated emotion (Fun, Stressful, Important, Boring).
- Mark todos as complete or incomplete.
- Delete todos (with confirmation for active ones).
- Filter todos by emotion.
- Sort todos by creation order.
- Persist data: Todos are saved locally.

## ✨ Features

- **Task Management**: Create, read, update (toggle status), and delete todos.
- **Categorization**: Assign emotions/categories to tasks.
- **Local Persistence**:
  - Saves the todo list to `localStorage` (`todos`).
- **Search & Filtering**:
  - Filter by Emotion (Fun, Stressful, Important, Boring).
  - Sort by Date (Newest/Oldest).
- **Visual Feedback**: Icons for actions and emotions using `lucide-react`.
- **Responsive UI**: Built with TailwindCSS for a mobile-friendly design.

## 🧰 Tech Stack

- React
- TypeScript
- TailwindCSS
- Vite
- Lucide React
- NPM
- ESLint

## 🚀 Installation

### Prerequisites

- Node.js 18+
- npm

### Install dependencies

```bash
npm install
```

### Run the App

```bash
npm run dev
```
