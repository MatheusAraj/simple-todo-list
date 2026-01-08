# React Clean Task Manager

> Modern task management application built with React, featuring advanced filtering, state management, and a minimalist design system.

<div align="center">
  
  ![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
  ![Vite](https://img.shields.io/badge/Vite-B73BFE?style=for-the-badge&logo=vite&logoColor=FFD62E)
  ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
  ![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

  ### [🚀 Live Demo](https://simple-todo-list-8n2q.vercel.app)

</div>

---

## 📋 Overview

A production-ready Single Page Application (SPA) demonstrating modern React development practices. This project goes beyond traditional to-do lists by implementing sophisticated filtering logic, optimized state management, and a scalable component architecture.

### Key Technical Highlights

- **Component Architecture**: Modular, reusable component design (`Todo`, `TodoForm`, `Search`, `Filter`)
- **State Management**: Advanced `useState` patterns with immutable state updates
- **Design System**: CSS custom properties for consistent theming and maintainability
- **Performance**: Optimized re-renders and efficient data filtering algorithms

---

## ⚙️ Features

| Feature | Implementation |
|---------|---------------|
| **CRUD Operations** | Full create, read, update, and delete functionality with real-time UI updates |
| **Real-time Search** | Instant task filtering with debounced input handling |
| **Category System** | Tag-based organization (Work, Personal, Study, etc.) |
| **Advanced Filters** | Multi-criteria filtering: All, Completed, or Pending tasks |
| **Dynamic Sorting** | Alphabetical ordering (A-Z / Z-A) with case-insensitive comparison |
| **Responsive Design** | Mobile-first approach with breakpoint optimization |

---

## 🛠️ Tech Stack

```
Frontend Framework:  React 18
Build Tool:          Vite
Styling:             CSS3 (Custom Properties)
State Management:    React Hooks (useState)
Deployment:          Vercel
Version Control:     Git
```

---

## 🚀 Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/MatheusAraj/simple-todo-list.git
   ```

2. **Navigate to project directory**
   ```bash
   cd simple-todo-list
   ```

3. **Install dependencies**
   ```bash
   npm install
   ```

4. **Start development server**
   ```bash
   npm run dev
   ```

5. **Access the application**
   
   Open your browser and navigate to URL displayed in your terminal

### Build for Production

```bash
npm run build
```

The optimized production build will be generated in the `dist/` directory.

---

## 📁 Project Structure

```
simple-todo-list/
├── src/
│   ├── components/
│   │   ├── Todo.jsx
│   │   ├── TodoForm.jsx
│   │   ├── Search.jsx
│   │   └── Filter.jsx
│   ├── App.jsx
│   ├── App.css
│   └── main.jsx
├── public/
├── package.json
└── vite.config.js
```

---

## 💡 Development Approach

This project emphasizes:

- **Clean Code Principles**: Readable, maintainable, and self-documenting code
- **Component Reusability**: DRY (Don't Repeat Yourself) methodology
- **State Immutability**: Proper React state management patterns
- **Separation of Concerns**: Clear distinction between UI and business logic
- **Performance Optimization**: Minimized unnecessary re-renders

---

## 🔗 Links

- **Live Application**: [https://simple-todo-list-8n2q.vercel.app](https://simple-todo-list-8n2q.vercel.app)
- **Repository**: [https://github.com/MatheusAraj/simple-todo-list](https://github.com/MatheusAraj/simple-todo-list)

---

## 👨‍💻 Author

**Matheus Araujo**

- GitHub: [@MatheusAraj](https://github.com/MatheusAraj)

---

<div align="center">
  <sub>Built with ⚛️ React and deployed on Vercel</sub>
</div>
