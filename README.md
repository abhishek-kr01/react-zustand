# React Zustand Practice

This repository is for learning and practicing state management in **React using Zustand**.  
It demonstrates how to manage global state using **feature-based stores**, selective subscriptions, and async API calls.

## 🚀 Tech Stack

- React (Vite)
- Zustand (State Management)
- JavaScript (ES6+)

## 📁 Project Structure
```
src/
├─ components/
│ ├─ Counter.jsx
│ ├─ CounterButton.jsx
│ ├─ CounterValue.jsx
│ ├─ Navbar.jsx
│ └─ Posts.jsx
│
├─ store/
│ ├─ appStore.js
│ ├─ counterStore.js
│ └─ postsStore.js
│
├─ App.jsx
└─ main.jsx
```

## 🧠 Zustand Stores

### ✅ Counter Store (`counterStore.js`)
Manages counter state and actions:
- count
- increase
- decrease
- reset

Used with selective subscriptions for better performance.

### ✅ App Store (`appStore.js`)
Manages application-level state:
- user authentication (login/logout)
- theme toggle (light/dark)

### ✅ Posts Store (`postsStore.js`)
Handles async API data:
- fetches posts from JSONPlaceholder API
- manages loading and error states

API Used:  
https://jsonplaceholder.typicode.com/posts?_limit=5

## 🎯 Key Concepts Practiced

- Feature-based Zustand stores
- Selective state subscriptions
- Async actions inside Zustand
- Global UI state handling
- Separation of concerns between UI and state
