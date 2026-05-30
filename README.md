# 🐱 Cat Trivia Quiz Project

A web development project demonstrating the progressive development of a Cat Trivia Quiz using HTML, CSS, and JavaScript.

This repository contains the final production version of the quiz, along with milestone versions that show how features were added throughout the development process.

---

# 📋 Project Overview

The Cat Trivia Quiz is an interactive web application designed to test users' knowledge of cats while demonstrating fundamental web development concepts.

## Technologies Used

- HTML5
- CSS3
- JavaScript 

---

# 🎯 Learning Objectives

This project demonstrates:

- HTML page structure
- CSS styling and layout
- JavaScript event handling
- Timers and countdown functionality
- Image integration
- User interaction and feedback
- Code organization and documentation

---

# 📁 Repository Structure

```text
cat-trivia-quiz/
│
├── final-version/
│   ├── index.html
│   ├── styles.css
│   └── script.js
│
├── versions/
│   ├── v1-basic-quiz/
│   ├── v2-add-timer/
│   └── v3-add-images/
│
├── documentation/
│   └── javascript-comments.md
│
└── README.md
```

---

# 🚀 Final Version Features

The completed Cat Trivia Quiz includes:

- Multiple-choice questions
- Cat-themed images
- Countdown timer
- Score calculation
- Answer validation
- Responsive design
- User-friendly interface

---

# 🔄 Development Versions

## Version 1: Basic Quiz

### Features

- HTML quiz structure
- Multiple-choice questions
- Submit button
- Basic scoring system
- No images
- No timer

### Skills Practiced

- HTML forms
- JavaScript functions
- Basic DOM manipulation

---

## Version 2: Timer Added

### New Features

- Countdown timer
- Automatic quiz submission when time expires
- Visual time display

### Skills Practiced

- JavaScript timers
- `setInterval()`
- Dynamic content updates

---

## Version 3: Images Added

### New Features

- Cat images for questions
- Enhanced visual design
- Improved user experience

### Skills Practiced

- Working with images
- HTML media elements
- CSS image styling

---

## Final Version

### Complete Feature Set

✅ Multiple-choice questions

✅ Countdown timer

✅ Cat images

✅ Score tracking

✅ Responsive styling

✅ Enhanced user interface

---

# 💻 JavaScript Commenting Guide

Comments make code easier to understand and maintain.

## Single-Line Comments

```javascript
// This is a single-line comment

let score = 0; // Stores the user's score
```

---

## Multi-Line Comments

```javascript
/*
This is a multi-line comment.

Use this style to explain
larger sections of code.
*/
```

---

## Function Documentation Example

```javascript
/**
 * Calculates the user's quiz score.
 * @param {number} correctAnswers
 * @returns {number}
 */
function calculateScore(correctAnswers) {
    return correctAnswers * 10;
}
```

---

# 📝 Example JavaScript Concepts Used

## Event Listeners

```javascript
submitButton.addEventListener("click", checkAnswers);
```

## Variables

```javascript
let score = 0;
let timeRemaining = 60;
```

## Conditional Statements

```javascript
if (selectedAnswer === correctAnswer) {
    score++;
}
```

## Functions

```javascript
function displayScore() {
    console.log(score);
}
```

---

# 🎨 CSS Concepts Used

- Selectors
- Classes and IDs
- Flexbox
- Responsive design
- Hover effects
- Colors and typography

Example:

```css
.quiz-container {
    max-width: 800px;
    margin: auto;
}
```

---

# 🏗 HTML Concepts Used

- Forms
- Radio buttons
- Images
- Buttons
- Semantic elements

Example:

```html
<img src="cat.jpg" alt="Cat Image">

<button type="submit">Submit Quiz</button>
```

---

# 📈 Development Progress

| Version | Features |
|----------|----------|
| V1 | Basic quiz functionality |
| V2 | Added countdown timer |
| V3 | Added cat images |
| Final | Complete polished quiz |

---

# 🎓 Skills Demonstrated

### Front-End Development

- HTML5
- CSS3
- JavaScript

### JavaScript Fundamentals

- Variables
- Functions
- Loops
- Conditionals
- Events
- Timers

### User Experience

- Interactive design
- Visual feedback
- Responsive layouts

---

# 📚 Key Takeaways

Through this project, I learned:

- How HTML, CSS, and JavaScript work together
- How to manipulate webpage elements using JavaScript
- How to create and manage timers
- How to organize code using comments and functions
- How to progressively enhance a web application

---

# 📜 License

This project was created for educational purposes as part of a web development course.

---

## Author

**[Your Name]**

Web Development Coursework • Cat Trivia Quiz Project
