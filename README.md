# Calculator

A clean, minimal calculator web app built with HTML, CSS, and JavaScript.

> A simple yet fully functional calculator supporting basic arithmetic operations with a two-line display showing both the current input and previous expression.

## Features

- **Basic arithmetic** — Addition, subtraction, multiplication, and division
- **Decimal support** — Enter floating-point numbers with the `.` button
- **Two-line display** — Shows the previous expression and the current input simultaneously
- **Delete (DEL)** — Erase the last entered digit without clearing everything
- **All Clear (AC)** — Resets the calculator to its initial state

## Usage

Open `calculator.html` in any modern browser. The app references external `calculator.css` and `calculator.js` files, so keep all three files in the same folder.

| Button | Action |
|--------|--------|
| `0–9` | Enter digits |
| `.` | Add a decimal point |
| `÷ × - +` | Choose an operation |
| `=` | Compute the result |
| `DEL` | Delete the last digit |
| `AC` | Clear everything |

## File Structure

```
├── calculator.html   # Markup and layout
├── calculator.css    # Styles (external)
└── calculator.js     # Logic via a `calculator` object (external)
```

## Browser Support

Works in all modern browsers (Chrome, Firefox, Safari, Edge) with no build step or internet connection required.
