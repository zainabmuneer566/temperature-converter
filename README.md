# Temperature Converter

A simple web tool that converts temperatures between Celsius, Fahrenheit and Kelvin, with real-time input validation.

**Live demo:** https://zainabmuneer566.github.io/temperature-converter/

## Features
- Numeric input with validation (non-numeric input shows an error message)
- Unit selector: Celsius, Fahrenheit or Kelvin
- Shows all three units at once
- Convert button (the Enter key also works)
- Absolute zero check (below -273.15°C, -459.67°F or 0 K shows an error)
- Clean, centred, responsive layout

## Technologies
HTML5, CSS3, JavaScript (Vanilla)

## Formulas
- Celsius to Fahrenheit: `F = C × 9/5 + 32`
- Fahrenheit to Celsius: `C = (F − 32) × 5/9`
- Celsius to Kelvin: `K = C + 273.15`
- Kelvin to Celsius: `C = K − 273.15`

## How to run
1. Download or clone this repository.
2. Open `index.html` in any web browser.

## What I learned
- How to convert between temperature scales using formulas
- How to validate user input with JavaScript (regular expressions and error messages)
- How to update the page with the DOM and handle events
