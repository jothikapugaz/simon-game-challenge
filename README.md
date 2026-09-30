# 🟢 Simon Game Challenge

A browser-based Simon game built with **HTML, CSS, JavaScript, and jQuery**. The project generates a sequence using four colored buttons and lets the player interact with the sequence using mouse clicks.

## ✨ Features

- 🎮 Four colored game buttons: green, red, yellow, and blue
- ⌨️ Press a keyboard key to start the game
- 🎲 Generates a random color for each new sequence
- 🔊 Plays a corresponding sound for each color
- ✨ Animates the selected color when the sequence is generated
- 🖱️ Lets the player click the colored buttons
- 💡 Provides visual feedback when a button is pressed
- 📈 Displays the current level on the page

## 🕹️ How to Play

1. Open `index.html` in a browser.
2. Press any keyboard key to start the game.
3. A color is randomly selected and displayed as the next sequence item.
4. The selected color plays its corresponding sound and animation.
5. Click the colored buttons to interact with the game.
6. The current level is displayed at the top of the page.

## 🛠️ Technologies Used

- **HTML5** – page structure and game buttons
- **CSS3** – layout, colors, button styling, and animations
- **JavaScript** – game state, random sequence generation, sound, and interaction
- **jQuery 3.7.1** – DOM selection, events, animations, and effects

## ⚙️ How It Works

The game maintains a list of four possible colors:

```text
red
blue
green
yellow
```

When the game starts, JavaScript randomly selects a color and adds it to the game pattern. The selected button is animated and its corresponding audio file is played.

When a player clicks a button, the clicked color is added to the user's click pattern, its sound is played, and the button receives a short visual animation.

The project currently focuses on the sequence generation and user interaction components of the Simon game. Sequence validation and game-over/restart handling can be added as future improvements.

## 📁 Project Structure

```text
simon-game-challenge/
├── index.html
├── game.js
├── styles.css
└── sounds/
    ├── red.mp3
    ├── blue.mp3
    ├── green.mp3
    └── yellow.mp3
```

## 🚀 Run Locally

1. Clone the repository:

```bash
git clone https://github.com/jothikapugaz/simon-game-challenge.git
```

2. Open the project folder in VS Code.
3. Make sure the `sounds` folder contains the required audio files.
4. Open `index.html` in a browser.
5. Press a keyboard key to start the game.

Because the project loads jQuery from Google's CDN, an internet connection is required for that dependency when running the page directly.

You can also use the **Live Server** extension in VS Code.

## 📚 What I Practiced

This project helped me practice:

- JavaScript arrays and variables
- Random number generation
- Event handling with jQuery
- DOM manipulation
- Click and keyboard events
- Audio playback with JavaScript
- CSS class manipulation
- jQuery animations such as `fadeIn()` and `fadeOut()`
- Managing basic game state

## 🔮 Possible Improvements

The current implementation can be extended by adding:

- Complete sequence validation
- Checking the user's input against the generated sequence
- Game-over handling when an incorrect sequence is entered
- Restart functionality
- Increasing sequence difficulty across levels
- A dedicated start/restart button
- Improved mobile and responsive support
- High-score tracking

## 👩‍💻 Author

**Jothika P**

Computer Science & Engineering graduate | Aspiring Full-Stack Developer

GitHub: [@jothikapugaz](https://github.com/jothikapugaz)
