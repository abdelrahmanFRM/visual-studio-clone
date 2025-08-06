# 🖥️ Visual Studio Clone

A modern, web-based **Visual Studio Clone** that mimics the layout and experience of the Visual Studio IDE. Built with **React** and **TypeScript**, the app includes **resizable UI panels**, **syntax-highlighted code blocks**, and **dynamic tab management** — all styled with **Tailwind CSS** and powered by **Redux** for global state handling.

---

## 🚀 Tech Stack

- **React** – UI component framework  
- **TypeScript** – Static typing and code scalability  
- **React Redux** – State management across the app  
- **@reduxjs/toolkit** – Simplified Redux setup (if used)  
- **react-resizable-panels** – Resizable, draggable layout panels  
- **react-syntax-highlighter** – Syntax-highlighted code rendering  
- **uuid** – Unique IDs for tabs, files, etc.  
- **Tailwind CSS** – Utility-first CSS framework  

---

## ✨ Key Features

- 🧩 **Resizable Panels** – Drag-and-resize vertical and horizontal UI panels  
- 🧠 **Global State Management with Redux** – Manage open tabs, editor states, and layout  
- 🧾 **Syntax-Highlighted Editor View** – Render code blocks with syntax coloring  
- 🧼 **Dynamic Tabs with UUIDs** – Safely manage tabs using unique identifiers  
- 💅 **Clean, Responsive UI** – Built with Tailwind CSS for responsiveness  

---

## 📁 Project Structure

src/
├── components/  # UI elements (tabs, editors, panels)
├── features/    # Redux slices for managing state
├── store/       # Redux store configuration
├── styles/      # Tailwind base or global styles
├── utils/       # Utility functions (UUID, helpers)
├── App.tsx      # Root component
└── index.tsx    # App entry point

