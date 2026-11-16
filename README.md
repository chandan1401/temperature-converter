# Temperature Converter

A responsive temperature converter built with HTML5, CSS3 and vanilla JavaScript.

## Features
- Convert between Celsius, Fahrenheit and Kelvin.
- Displays all three units at the same time.
- Validates empty and invalid numeric input.
- Rejects temperatures below absolute zero.
- Responsive layout for desktop and mobile.
- Accessible labels and inline error feedback.

## Run locally
1. Download and extract the project.
2. Open the `temperature-converter` folder.
3. Double-click `index.html` to open it in your browser.

No installation, API key, framework or build step is required.

## Conversion formulas
- Celsius to Fahrenheit: `(C × 9/5) + 32`
- Fahrenheit to Celsius: `(F − 32) × 5/9`
- Celsius to Kelvin: `C + 273.15`
- Kelvin to Celsius: `K − 273.15`

The app converts the input to Celsius first, then calculates the other two values.

## Project structure
```text
temperature-converter/
├── index.html
├── style.css
├── script.js
└── README.md
```
