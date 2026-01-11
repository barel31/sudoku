# Sudoku Game

A web-based Sudoku puzzle game built with HTML, CSS, and JavaScript.

## Description

This is an interactive Sudoku game that allows players to solve puzzles of varying difficulty levels. The game features a sign-in system, timer, hints, and automatic validation.

## Features

- **User Authentication**: Simple sign-in with username and password
- **Difficulty Levels**: Easy, Medium, Hard, and Custom difficulty options
- **Timer**: Tracks the time spent solving the puzzle
- **Hints**: Provides hints to help players when stuck
- **Auto-Check**: Automatically validates moves as you play
- **Responsive Design**: Works on different screen sizes

## Authors

- Barel Shraga
- Anton Varakuta

## How to Play

1. Open `index.html` in your web browser
2. Sign in with the default credentials:
   - Username: `abcd`
   - Password: `1234`
3. Choose your difficulty level or select Custom to specify the number of pre-filled cells
4. Fill in the Sudoku grid following the rules:
   - Each row must contain digits 1-9
   - Each column must contain digits 1-9
   - Each 3x3 subgrid must contain digits 1-9
5. Use the Hint button if you need help
6. Click Finish when you think you've solved it

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- Bootstrap 5
- jQuery

## File Structure

```
sudoku/
├── index.html          # Sign-in page
├── index.js            # Sign-in logic
├── game.html           # Game page
├── game.js             # Game logic and board generation
├── css/
│   ├── index.css       # Styles for sign-in page
│   ├── game.css        # Styles for game page
│   ├── loader.css      # Loading animation styles
│   └── checkbox-custom.css  # Custom checkbox styles
└── images/
    └── icon.png        # Game icon
```

## Running the Game

Simply open `index.html` in any modern web browser. No server or build process is required.

## Browser Compatibility

- Chrome (recommended)
- Firefox
- Safari
- Edge

## License

This project is for educational purposes. © Barel Shraga & Anton Varakuta