# Task 3: Advanced Styling and JavaScript 🚀

## 📋 Overview
This project satisfies the requirements for **Task 3**, focusing on building interactive, responsive web applications using advanced CSS and asynchronous JavaScript. 

The application features two distinct sections:
1.  **🧠 Live Programming Quiz:** Fetches real-time computer science questions from an external API.
2.  **💬 Quote Generator:** Asynchronously retrieves inspirational quotes.

## ✨ Features

### 1. Responsive Design (CSS)
* **Mobile-First Approach:** The layout adapts seamlessly to different screen sizes.
* **Media Queries:** Implemented breakpoints (max-width: 650px) to switch from Grid views to stacked layouts for mobile devices.
* **Modern Styling:** Used CSS Variables (`:root`), Flexbox, and CSS Grid for a clean, maintainable UI.

### 2. Interactive Logic (JavaScript)
* **Dynamic DOM Manipulation:** Elements are created and destroyed dynamically based on user interaction (e.g., loading new questions, showing results).
* **Game State Management:** Tracks current score, question progress, and handles "Game Over" states.
* **Randomization:** Answer options are shuffled so the correct answer isn't in the same spot every time.

### 3. API Integration (Fetch API)
* **Async/Await:** Used modern ES6+ syntax to handle asynchronous data fetching.
* **Error Handling:** Includes `try...catch` blocks to handle network errors or API limits gracefully.
* **Loading States:** Visual spinners indicate when data is being fetched from the server.

## 🛠️ Technologies Used
* **HTML5**
* **CSS3** (Variables, Animations, Flexbox, Grid)
* **JavaScript** (ES6+, DOM, Fetch API)

## 🔌 APIs Used
* **Open Trivia DB:** Used to fetch multiple-choice questions for the "Computers" category.
    * *Endpoint:* `https://opentdb.com/api.php?amount=10&category=18&type=multiple`
* **DummyJSON:** Used to fetch random quotes.
    * *Endpoint:* `https://dummyjson.com/quotes/random`

## 🚀 How to Run
1.  Clone the repository or download the source code.
2.  Locate the `program3.html` file.
3.  Double-click to open it in any modern web browser (Chrome, Firefox, Edge).
4.  *Note:* An internet connection is required for the APIs to function.

---
**Completed by:** [Tejaswini.Beri]
