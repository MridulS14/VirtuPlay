
# VirtuPlay 🎮

VirtuPlay is an interactive game project built in Python using OpenCV, MediaPipe, and the cvzone library. It includes two gesture-controlled games:

1. **Ping Pong** 🏓
2. **Hungry Snake** 🐍

Players control the games using hand gestures tracked by a webcam.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [How to Play](#how-to-play)
- [Screenshots](#screenshots)
- [Technologies Used](#technologies-used)
- [Future Enhancements](#future-enhancements)
- [Contributing](#contributing)
- [License](#license)

## Overview
VirtuPlay is an immersive gaming experience where you control the action with your hands! This project uses hand tracking to let you play two classic games:
- **Ping Pong:** A fun 2D ping pong game where you control the paddles with hand gestures.
- **Hungry Snake:** A snake game where you guide the snake to the food by moving your hand.

## Features
- **Real-time Hand Tracking:** Control the game with hand movements using your webcam.
- **Two Exciting Games:** Switch between Ping Pong and Hungry Snake.
- **Interactive Gameplay:** Completely touch-free gaming experience.
- **Dynamic Score Tracking:** Tracks your progress and performance in each game.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/VirtuPlay.git
    cd VirtuPlay
    ```

2. Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```

3. Download or create a folder `Resources/` in your project directory with the following image assets:
    - `start.png` (Ping Pong Start Screen)
    - `khatm.png` (Ping Pong End Screen)
    - `ball.png` (Ping Pong Ball)
    - `bat1.png` (Player 1 Paddle)
    - `bat2.png` (Player 2 Paddle)
    - `laddoo.png` (Food for Snake Game)
    - `bg.jpg` (Background Image)

## How to Play

1. **Launch the Application:**
   - Run the script by executing `python virtuplay.py`.

2. **Select a Game:**
   - The main window allows you to choose between Ping Pong and Hungry Snake. Click on the game you want to play.

### Game Controls
- **Ping Pong:** Use your hands to move the paddles on either side of the screen. The game tracks your hand position using your webcam.
- **Hungry Snake:** Control the snake by moving your hand. Guide the snake to eat food while avoiding hitting itself.

### Restart a Game
Press `r` during gameplay to reset and restart the game.

## Screenshots
**Main Menu**
![Main Menu](screenshots/menu.png)

**Ping Pong**
![Ping Pong](screenshots/pingpong.png)

**Hungry Snake**
![Hungry Snake](screenshots/snake.png)

## Technologies Used
- **Python** 🐍
- **OpenCV** for video capture and image processing.
- **MediaPipe** for hand gesture detection and tracking.
- **cvzone** for game mechanics and overlaying images.
- **Tkinter** for the GUI window and buttons.

## Future Enhancements
- **Multiplayer Mode:** Add the option to connect two players online.
- **More Games:** Incorporate additional gesture-based games.
- **Difficulty Levels:** Add levels to make the games more challenging.
- **Scoreboard:** Save and display top scores.

## Contributing
Feel free to fork this repository and contribute to the project. Pull requests are welcome for any improvements or bug fixes.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
