# Tic-Tac-Toe MERN Stack Game

Welcome to the Tic-Tac-Toe MERN Stack Game! This application allows users to play the classic game of Tic-Tac-Toe using the MERN stack (MongoDB, Express.js, React.js, Node.js).

## Features

- Play Tic-Tac-Toe against another player in real-time.
- User-friendly interface designed with React.js.
- Backend server built with Node.js and Express.js.
- Game data stored in a JSON file using Node.js's file write method.
- Real-time updates using WebSockets for seamless gameplay.

## Installation

To run the Tic-Tac-Toe MERN Stack Game locally, follow these steps:

1. Clone the repository to your local machine:

   ```
   git clone https://github.com/starshows/tic-tac-toe-mern.git
   ```

2. Navigate to the project directory:

   ```
   cd tic-tac-toe-mern
   ```

3. Install server dependencies:

   ```
   npm install
   ```

4. Navigate to the client directory:

   ```
   cd client
   ```

5. Install client dependencies:

   ```
   npm install
   ```

6. Go back to the root directory:

   ```
   cd ..
   ```

7. Start the development server:

   ```
   npm run dev
   ```

8. Open your web browser and go to `http://localhost:3000` to view the application.

## Usage

- Register an account or log in to start playing.
- Once logged in, you can create a new game or join an existing game.
- Invite your friend to play by sharing the game room link.
- Click on the grid to make your move.
- The game automatically detects wins and ties and updates the scoreboard accordingly.

## Technologies Used

- Express.js: Web application framework used for building the backend server.
- React.js: JavaScript library used for building the user interface.
- Node.js: JavaScript runtime environment used for server-side scripting.
- Socket.IO: JavaScript library for real-time web applications.
- HTML/CSS: Markup and styling languages for designing the UI.

## Data Storage

Game data is stored in a JSON file using Node.js's file write method. This allows for simple data management without the need for a separate database system.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests to help improve the application.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

[Alex Tannenbaum](https://github.com/starshows)

## Acknowledgments

- Special thanks to the developers of the MERN stack and Socket.IO for making real-time web applications possible.
- Inspired by the classic game of Tic-Tac-Toe.
- Hat tip to anyone whose code was used as a reference.