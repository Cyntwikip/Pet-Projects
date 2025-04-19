# Tic-Tac-Toe React App

This is a simple Tic-Tac-Toe game built with React. The project is based on the official [React tutorial](https://react.dev/learn/tutorial-tic-tac-toe) and demonstrates key React concepts such as components, state, and props.

## Features

- Play a two-player Tic-Tac-Toe game.
- Tracks the history of moves, allowing players to jump back to previous game states.
- Displays the winner or the next player.

## Getting Started

### Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/) (version 14 or higher)
- [npm](https://www.npmjs.com/) (comes with Node.js)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Cyntwikip/Pet-Projects.git
cd Pet-Projects/tic-tac-toe_react
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm start
```

4. Open your browser and navigate to `http://localhost:3000` to play the game.

## Project Structure

- **`src/App.js`**: Contains the main game logic and React components (`Game`, `Board`, `Square`).
- **`src/index.js`**: Entry point for the React application.
- **`public/`**: Contains the static files for the app.

## How It Works

The game is divided into three main components:

1. **`Square`**: Represents a single square on the board.
2. **`Board`**: Manages the state of the 3x3 grid and determines the winner.
3. **`Game`**: Tracks the history of moves and allows players to navigate through them.

The `calculateWinner` function checks for a winning combination after every move.

## Learn More

This project is based on the official [React Tic-Tac-Toe tutorial](https://react.dev/learn/tutorial-tic-tac-toe). Visit the tutorial to learn more about the concepts used in this project.

## License

This project is open-source and available under the [MIT License](LICENSE).

## Acknowledgments

- [React Documentation](https://react.dev/)
- [React Tic-Tac-Toe Tutorial](https://react.dev/learn/tutorial-tic-tac-toe)
