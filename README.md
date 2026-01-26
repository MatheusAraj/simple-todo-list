# React Clean Task Manager

> High-performance Single Page Application (SPA) for task management, developed with React and Vite, focused on modular design principles and immutable state management.

<div align="center">

  ![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
  ![Vite](https://img.shields.io/badge/Vite-B73BFE?style=for-the-badge&logo=vite&logoColor=FFD62E)
  ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
  ![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

  ### [Access the demo (Live Demo)](https://simple-todo-list-8n2q.vercel.app)

</div>

---

## Overview

This project is a robust application that demonstrates contemporary frontend development practices. The implementation focuses on scalable component architecture, complex filtering logic, and optimized data flow.

### Architecture and Engineering

- **Modularization**: Strict separation of responsibilities between UI components (`Todo`, `TodoForm`) and control logic (`Search`, `Filter`).
- **State Management**: Strategic use of React Hooks for handling global and local states, ensuring data persistence and integrity throughout the application lifecycle.
- **Styling Systems**: Implementation of CSS Custom Properties (CSS Variables) to ensure visual consistency and facilitate theme maintenance.
- **Filtering Algorithms**: Optimized array processing logic, enabling real-time search and sorting with low latency.

---

## Technical Features

| Module | Technical Description |
|---------|----------------------|
| **CRUD Operations** | Real-time state persistence with reactive UI updates. |
| **Search Engine** | Dynamic string filtering integrated into the rendering flow. |
| **Category Taxonomy** | Tag-based system for semantic task classification (Work, Personal, Studies). |
| **Multi-criteria Filtering** | Conditional logic implementation for states: "All", "Completed", and "Pending". |
| **Data Sorting** | Alphabetical sorting algorithms (ASC/DESC) with case-insensitivity handling. |
| **Responsive Design** | Architecture based on Media Queries and Flexbox for cross-device compatibility. |

---

## Technology Stack

- **Core**: React 18
- **Build Tooling**: Vite
- **Styling Engine**: CSS3 (Modular)
- **State Management**: Functional Components & Hooks
- **Deployment**: Vercel CI/CD
- **Version Control**: Git

---

## Environment Setup

### Prerequisites

- Node.js (Runtime environment v16.0.0+)
- npm or yarn package manager

### Installation Procedure

1. **Repository cloning**

```bash
git clone https://github.com/MatheusAraj/simple-todo-list.git

```

2. **Directory navigation**

```bash
cd simple-todo-list

```

3. **Dependency installation**

```bash
npm install

```

4. **Run development environment**

```bash
npm run dev

```

### Deployment (Production Build)

To generate optimized production artifacts in the `/dist` directory:

```bash
npm run build

```

---

## Directory Structure

```text
simple-todo-list/
├── src/
│   ├── components/       # Reusable UI components
│   │   ├── Todo.jsx      # Individual task item
│   │   ├── TodoForm.jsx  # Creation logic
│   │   ├── Search.jsx    # Search component
│   │   └── Filter.jsx    # Filtering and sorting logic
│   ├── App.jsx           # Root component and state orchestrator
│   ├── App.css           # Global definitions and variables
│   └── main.jsx          # Application entry point
├── package.json          # Project manifest and scripts
└── vite.config.js        # Bundler configuration

```

---

## Development Principles

The application was structured following these guidelines:

* **Clean Code**: Readable and semantic code.
* **DRY (Don't Repeat Yourself)**: Logical redundancy minimization through generic components.
* **Immutability**: State integrity guaranteed through non-destructive update patterns.
* **Separation of Concerns (SoC)**: Clear division between business logic and visual presentation.

---

## Contact and Repository

* **Application**: [https://simple-todo-list-8n2q.vercel.app](https://simple-todo-list-8n2q.vercel.app)
* **Developer**: [Matheus Araujo](https://github.com/MatheusAraj)

---

<div align="center">
<sub>Developed under modern software engineering standards with React.</sub>
</div>
