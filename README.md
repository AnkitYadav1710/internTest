# Random Background Color Generator

A simple and interactive web application built using HTML, CSS, and JavaScript that generates random HEX color codes and dynamically changes the webpage background.

The application also uses Browser Local Storage to save the last selected background color and restore it automatically when the webpage is refreshed.

## Source code

[Github Repository](https://github.com/AnkitYadav1710/internTest)
[Code](https://github.com/AnkitYadav1710/internTest/blob/main/index.html)

## Features

- **Random HEX Color Generation:** Generates random six-digit HEX color codes.
- **Dynamic Background:** Changes the webpage background color when the user clicks the button.
- **Color Code Display:** Displays the currently applied HEX color code on the webpage.
- **Local Storage:** Saves the selected background color in the browser.
- **Color Persistence:** Retrieves and applies the previously saved color when the webpage is reopened or refreshed.
- **Smooth Transition:** Includes a smooth background color transition effect.

## Technologies Used

- **HTML5:** Structures the webpage and its elements.
- **CSS3:** Handles styling, layout, button appearance, and transitions.
- **JavaScript:** Implements random color generation and DOM manipulation.
- **Browser Local Storage API:** Stores and retrieves the previously selected background color.

## How It Works

1. When the webpage loads, JavaScript checks Local Storage for a previously saved background color.
2. If a saved color exists, it is retrieved and applied to the webpage.
3. When the user clicks the "Change Color" button, a random six-digit HEX color is generated.
4. The generated color is applied to the webpage, and its HEX code is displayed.
5. The newly generated color is saved in Local Storage using the key `savedBgColor`.
6. When the webpage is refreshed, the last saved color is retrieved and applied automatically.

## Project Structure

```text
Random-Background-Color-Generator/
│
├── index.html
└── README.md
```

The HTML, CSS, and JavaScript code are all contained within a single `index.html` file.

## How to Run the Project

1. Clone the repository:
   `bash git clone YOUR_GITHUB_REPOSITORY_URL`

2. Navigate to the project folder.
3. Open `index.html` in your web browser.
4. Click the **Change Color** button to generate random background colors.

## Concepts Practised

- JavaScript functions and loops.
- `Math.random()` and `Math.floor()`.
- String indexing and concatenation.
- DOM manipulation.
- Event listeners (`addEventListener`).
- Browser Local Storage (`getItem()` and `setItem()`).
- HEX color codes.
- Updating webpage styles dynamically.

## Author

**Ankit Yadav**
