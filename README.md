# Notes Management App (React)

A simple Notes Management application built using React.  
This project was developed as part of a frontend assessment to demonstrate clean component architecture, proper state management, and thoughtful UI state handling.

---

## 🚀 Features

- Add notes with a required title and optional description
- View a list of created notes
- Delete notes instantly
- Handles loading, empty, and validation error states
- Clean and minimal user interface

---

## 🛠️ Tech Stack

- React JS (Vite)
- JavaScript (ES6+)
- CSS (no external UI libraries)

---

## 📂 Project Structure

src/
├─ components/
│ ├─ NoteForm.jsx
│ ├─ NoteList.jsx
│ ├─ NoteItem.jsx
│ ├─ Loader.jsx
│ └─ EmptyState.jsx
├─ App.jsx
├─ main.jsx
└─ index.css

---

## 🧠 State Management Approach

- All application state is managed in `App.jsx` using React's `useState`
- Notes data and handler functions are passed via props
- No external state management libraries are used
- Loading state is simulated using `useEffect`

---

## 🎭 UI States Handled

- **Loading State** – shown on initial app load
- **Empty State** – shown when no notes exist
- **Error State** – inline validation when title is missing

---

## ▶️ How to Run the Project

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
3. Start the development server:
   npm run dev
4. Open in browser:
   http://localhost:5173/
   

