# Typing Speed Test Application

A simple web application that measures your **typing speed (WPM)** and **accuracy** using a sample passage and a countdown timer.

**Level:** Practical  |  **Project No.:** 18

## Features
- Random sample passage on every new test
- Selectable duration: 30, 60 or 120 seconds
- Timer starts automatically on the first key press
- Live WPM and accuracy while typing
- Correct letters in green, mistakes highlighted in red, current letter marked
- Final result with best score of the session
- Responsive design with automatic light/dark mode

## Folder Structure
```
typing_speed_test/
|-- index.html        -> Main page (HTML + CSS + JavaScript)
|-- README.md         -> Project documentation
`-- images/
    |-- logo.svg      -> Logo shown in the page heading
    |-- favicon.svg   -> Browser tab icon
    `-- banner.svg    -> Banner image for documentation / presentation
```

## Technologies Used
- HTML5
- CSS3 (CSS variables, flexbox, dark mode)
- JavaScript (DOM manipulation, timers, events)

## How to Run
1. Download or extract the `typing_speed_test` folder.
2. Open `index.html` in any modern browser (Chrome, Edge, Firefox).
3. No installation or internet connection required.

## How It Works
- **Accuracy** = (correct characters / total typed characters) x 100
- **WPM** = (correct characters / 5) / minutes elapsed  
  (one "word" is counted as 5 characters, the standard typing-test convention)
- The passage is redrawn on every key press, comparing each typed character with the original.
- The test ends when the timer reaches 0 or the full passage is typed.

## Possible Improvements
- More passages and difficulty levels
- Leaderboard saved in Local Storage
- Sound effects and keyboard on-screen layout
