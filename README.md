# LM Box 5

## Description
LM Box 5 is an interactive gaming platform that combines computer vision with classic games. The platform uses hand and body pose detection to enable players to control games through physical movements.

## Features
- **Main Menu Interface:** Sleek game selection menu with customizable settings
- **Dino Game:** A T-Rex runner clone controlled by body movements (jump/duck)
- **Camera Controls:** Play games using your webcam through pose detection
- **Custom Settings:** Adjustable difficulty, sound, music volume and display settings

## Games Included
1. **Dino Game:** Jump over cacti and dodge pterodactyls by moving your body up and down
   - Pink background for better visualization
   - Enlarged character and obstacles for improved gameplay
   - Camera overlay showing your movements

## Technical Requirements
- Python 3.8 or higher
- Pygame
- OpenCV
- Mediapipe
- CVZone (for hand detection)
- Screen resolution of 1280x720 or higher recommended

## Installation
1. Clone the repository
2. Install the dependencies:
```bash
pip install -r requirements.txt
```
3. Run the game:
```bash
python main.py
```

## Controls
- **Camera Controls:** Position yourself in front of the camera
  - Move your head up to jump
  - Move your head down to duck
- **Keyboard Fallback:** If camera controls aren't working
  - Space/Up Arrow: Jump
  - Down Arrow: Duck
  - ESC: Return to menu

## Project Structure
- `/gui`: Main game GUI and individual game implementations
- `/models`: Computer vision implementations for pose and hand tracking
- `/utils`: Utility functions for the application

## Credits
- Built with Pygame and Mediapipe
- Font: Press Start 2P
- Sound effects: Creative Commons licensed

LM Box 5 is a Python-based gaming platform that features interactive games controlled through computer vision. Using hand gesture and pose detection, users can play games like the Dino Runner with natural movements.

## Features

- Interactive dinosaur runner game with pink background and enlarged character/obstacles
- Hand gesture and pose detection for controlling games
- Cross-platform compatibility (Windows, macOS, Linux)
- Simple settings menu for adjusting game preferences

## Requirements

- Python 3.8+
- Pygame
- Pygame_menu
- OpenCV (cv2)
- MediaPipe
- CVZone
- NumPy
- SQLite3

## Installation

1. Clone this repository:
```
git clone https://github.com/yourusername/lm-box-5.git
cd lm-box-5
```

2. Install required packages:
```
pip install -r requirements.txt
```

## Usage

Run the main application:
```
python main.py
```

## Project Structure

- `main.py`: Entry point for the application
- `gui/`: Main GUI implementation and game modules
- `models/`: Computer vision models for hand tracking
- `utils/`: Utility functions

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
