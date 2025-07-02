# Calculator-JS-# 🧮 Bootstrap Calculator

A simple and responsive calculator built with **HTML**, **Bootstrap 5**, and **JavaScript**. It performs basic arithmetic operations with a clean and modern UI.

## 📦 Features

- Responsive layout using Bootstrap grid system
- Supports:
  - Addition (+)
  - Subtraction (-)
  - Multiplication (*)
  - Division (/)
- Clear button (`C`)
- Clear All button (`Clear All`)
- Equals button (`=`)
- Easy-to-use number and operator buttons

## 🚀 Technologies Used

- HTML5
- Bootstrap 5
- JavaScript (Vanilla)

## 📁 Project Structure

📁 project-folder/
├── index.html # Main HTML file with Bootstrap layout
├── script.js # JavaScript logic for button interaction and evaluation
└── README.md # Project documentation

markdown
Copy
Edit

## 💡 How It Works

1. Each button has either a `data-value` or `data-action` attribute.
2. JavaScript listens for button clicks:
   - If `data-value` is present → appends value to display.
   - If `data-action="calculate"` → evaluates the expression using `eval()`.
   - If `data-action="clear"` → clears the input.
3. The display is updated dynamically in real-time.

## 📜 License

This project is licensed under the MIT License.

## 👨‍💻 Author
acefnlaatiri
