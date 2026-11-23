# Node Coin Flip Game

A simple coin-flip guessing game built with Node.js. Choose Heads or Tails, flip the coin, and see whether your guess was correct. The game keeps track of your wins and total rounds as you play.

**Live demo:** [Play Node Coin Flip](https://node-coin-flip-bootcamp-lefu.onrender.com)

## Features

- Choose Heads or Tails before flipping.
- Randomly generate a coin-flip result.
- See whether your guess wins or loses.
- Track wins and total rounds.
- Play additional rounds without resetting your score.

## Built with

- Node.js built-in `http` module for the web server.
- Node.js built-in `fs` module to read and serve the HTML file.
- HTML, CSS, and vanilla JavaScript for the game interface and interactions.

No third-party npm packages are required.

## Run locally

1. Clone the repository:

   ```bash
   git clone https://github.com/Nlewi-glitch089/node-coin-flip-bootcamp.git
   cd node-coin-flip-bootcamp
   ```

2. Switch to the completed implementation branch:

   ```bash
   git switch answer
   ```

3. Start the server:

   ```bash
   node server.js
   ```

4. Open [http://localhost:3000](http://localhost:3000) in your browser.

The server uses the port assigned by the hosting environment when deployed, and defaults to port `3000` locally.

## Project context

This project began as a Resilient Coders / bootcamp exercise focused on using Node.js's built-in HTTP and filesystem modules to serve a web page. The completed implementation is maintained on the `answer` branch.
