# Stacky

[Stacky](https://avi4h.github.io/stacky/) is a simple 3D stacking game built with JavaScript and the Three.js and Cannon.js libraries. The goal of the game is to stack blocks on top of each other as high as possible without letting them fall off the edge. You can control the game by clicking, tapping, or pressing the spacebar to place blocks and build your tower.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [How to Play](#how-to-play)
- [Game Controls](#game-controls)
- [Game Mechanics](#game-mechanics)
- [Contributing](#contributing)
- [License](#license)

## Features

- 3D graphics with physics-based block stacking.
- Responsive design for various screen sizes.
- Autopilot mode for hands-free play.
- Real-time scoring to track your progress.

## Getting Started

### Prerequisites

Before you start, make sure you have the following software installed:

- [Node.js](https://nodejs.org/) (for serving the game locally)

### Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/avi4h/stacky.git
   ```

2. Navigate to the project directory:

   ```bash
   cd stacky

3. Install the required dependencies:

   ```bash
   npm install
   ```

4. Start the local development server:

   ```bash
   npm start
   ```
   
5. Open your web browser and visit [link](http://localhost:3000) to play the game.

## How to Play

- The game starts with a foundation block at the bottom.
- Your goal is to stack blocks on top of each other as high as possible.
- Click, tap, or press the spacebar to place blocks.
- Aim to align the new block with the previous one to prevent overhangs.
- If a block falls off the edge, the game ends.

## Game Controls

- **Mouse Click** : Place a block.
- **Touch(Mobile)** : Place a block.
- **Spacebar** : Place a block.
- **R Key** : Restart the game.

## Game Mechanics

- Each block has a random color.
- The tower moves upward automatically.
- Overlapping blocks get cut to fit perfectly.
- Missed placements result in overhangs.
- The game ends when a block falls off the tower.
- Your score is displayed on the top-right corner.

## Contributing

If you'd like to contribute to Stacky, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your changes to your fork.
5. Submit a pull request to the main repository.
6. 
Please ensure your code follows best practices and includes appropriate documentation if necessary.

## License

This project is licensed under the MIT License - see the [LICENSE](https://creativecommons.org/licenses/by-nc/4.0/) file for details.




