# Chess Snake & Ladder Game

A modern implementation of the classic Snake and Ladder game with a chess theme, built using React.

## Features

- Chess-themed game board with chess piece player tokens
- 3D animated dice using Three.js
- Realistic game animations and transitions
- Snakes and ladders with chess-inspired design
- Responsive design for different screen sizes

## Technologies Used

- React.js for the frontend UI
- Three.js for 3D dice animation
- Styled Components for styling
- Express.js for the backend server

## Installation

1. Clone the repository
```
git clone <repository-url>
cd chess-snake-ladder
```

2. Install dependencies for server and client
```
npm install
npm run install-client
```

3. Run the development server
```
npm run dev
```

This will start both the backend server and the React development server.

## How to Play

1. Select your chess piece (King, Queen, Rook, or Knight)
2. Click "Start Game" to begin
3. Roll the dice by clicking the "Roll Dice" button
4. Your piece will automatically move according to the dice value
5. Land on a ladder to climb up, or beware of snakes that will make you slide down
6. First player to reach square 100 wins!

## Game Rules

- Players take turns rolling the dice
- Move your piece the number of squares shown on the dice
- If you land on the bottom of a ladder, you climb up to the top
- If you land on the head of a snake, you slide down to its tail
- You must land exactly on square 100 to win
- If your roll would take you beyond square 100, you don't move

## Author:- Aniket Zimane
