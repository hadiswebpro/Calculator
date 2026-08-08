# 🧮 Calculator

A responsive calculator built with **HTML, CSS, and JavaScript**.

This project was created to practice JavaScript fundamentals and build a functional calculator with a clean and responsive interface.

## ✨ Features

* Basic arithmetic operations
* Addition, subtraction, multiplication, and division
* Real percentage calculations
* Decimal number support
* Delete and clear buttons
* Division-by-zero error handling
* Calculation result formatting
* Calculation history
* History saved with `localStorage`
* Maximum of 12 history items
* Dark mode
* Dark mode preference saved in `localStorage`
* Button sounds
* Sound on/off toggle
* Keyboard support
* Responsive design for different screen sizes

## 🛠️ Technologies

* HTML5
* CSS3
* JavaScript
* Local Storage API
* Web Audio API

## 📚 What I Practiced

While building this project, I practiced:

* DOM selection and manipulation
* `addEventListener`
* JavaScript functions
* `if / else` conditions
* Arrays and objects
* `forEach`
* Template literals
* `JSON.stringify()` and `JSON.parse()`
* `localStorage`
* Keyboard events with `keydown`
* Working with the `Audio` API
* Responsive CSS
* Dark mode implementation
* Error handling

## 🎯 Main JavaScript Concepts

The calculator separates its logic into different functions, including:

* `getNumbers()` — handles number input
* `getOperator()` — handles operators
* `calculate()` — performs calculations
* `addToHistory()` — saves calculations
* `showHistory()` — displays saved calculations
* `playSound()` — controls calculator sounds

## 📁 Project Structure

```text
Calculator/
│
├── index.html
├── README.md
│
└── sound/
    ├── number.mp3
    ├── operator.mp3
    ├── equal.mp3
    ├── error.mp3
    ├── ui.mp3
    └── ac.mp3
```

## 🚀 How to Run

No installation or external dependencies are required.

Simply open `index.html` in a browser.

## 🔮 Future Improvements

Possible future improvements:

* Delete individual history items
* Add a clear history button
* Add more advanced mathematical operations
* Improve keyboard shortcuts
* Add calculation animations
* Improve accessibility

## 👩‍💻 Author

**Hadis Rezaee**

Built as a JavaScript practice project.
