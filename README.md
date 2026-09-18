🎮 Tic Tac Toe Game

A simple and interactive Tic Tac Toe game built using HTML, CSS, and JavaScript (ES6).
The game supports two-player turn-based gameplay with automatic winner and draw detection.

🌐 Live Demo

Play the game here:

👉 Live Demo

🚀 Features

Turn-based Gameplay: Players take turns between O and X.

Winner Detection: Checks all 8 winning combinations — rows, columns, and diagonals — after every move.

Draw Detection: Automatically detects when all 9 boxes are filled without a winner.

Move Locking: Prevents players from clicking a box more than once.

Winner Message: Displays a congratulations message when a player wins.

New Game & Restart: Allows the game to be started again at any time.

Responsive Layout: Uses CSS Flexbox and viewport-based sizing for a clean layout across screen sizes.

🛠️ Built With

HTML5 — Page structure and game board layout.

CSS3 — Styling, layout, hover effects, and responsive sizing.

JavaScript (ES6) — DOM manipulation, click handling, turn management, and game logic.

📁 Project Structure

tic-tac-toe-game/
│
├── index.html      # Main HTML structure and game board
├── style.css       # Styling and responsive layout
├── app.js          # Game logic and event handling
└── README.md       # Project documentation

🧠 How the Game Works

The game starts with Player O.

Players click an empty box to place their mark.

The turn automatically switches between O and X.

After every move, JavaScript checks the predefined winning patterns.

If a player completes a row, column, or diagonal, the winner message is displayed.

If all 9 boxes are filled without a winner, the game is declared a draw.

New Game or Restart Game resets the board.

📌 Winning Patterns

The game checks these 8 possible combinations:

3 rows

3 columns

2 diagonals

💻 Run Locally

Clone the repository:

git clone https://github.com/hukamsingh-rathore/tic-tac-toe-game.git

Open the project folder.

Open index.html in your browser.

No external libraries or backend setup are required.

📸 Preview

The game provides a simple 3×3 board with separate controls for restarting the game and starting a new game after a result.

👨‍💻 Author

Hukam Singh Rathore

Built as a beginner-friendly web development project to practice HTML, CSS, JavaScript, DOM manipulation, and basic game logic.
