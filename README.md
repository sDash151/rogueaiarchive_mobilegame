# The Rogue AI's Archive - Mobile Edition

**The Rogue AI's Archive** is an immersive 3D escape room experience designed for mobile devices. Players find themselves trapped in a digital prison controlled by a rogue AI named A.R.I.A., and must solve puzzles across interconnected rooms to escape before being permanently deleted.

## Features

- 🕹️ **Mobile-first 3D environment** built with Three.js
- 🧠 **Multiple puzzle types**: Password entry, Simon pattern memory, and binary logic puzzles
- ⏳ **Time pressure** with a 30-minute countdown timer
- 🏃 **Dual control modes**: Look around and movement controls
- 📱 **Responsive design** that works on all screen sizes
- 🌌 **Atmospheric sci-fi setting** with glowing interfaces and digital effects
- 🔒 **Progressive puzzle solving** with interconnected solutions
- 🏆 **Win/lose conditions** with different endings

## How to Play

### Objective
Navigate through digital rooms, solve puzzles, and escape before A.R.I.A. completes your defragmentation (deletion).

### Controls:
- **Look Mode (👁️)**: Drag to look around
- **Move Mode (🚶)**: Drag to move through the environment
- **Tap objects** to interact with them

### Puzzle Types:
1. **Password Puzzle**: Solve the riddle to gain access
2. **Simon Puzzle**: Memorize and repeat color sequences
3. **Binary Lock**: Set the correct binary combination

### Game Flow:
1. Restore power to access the terminal
2. Solve the password puzzle to get the logic key
3. Travel to the data stream room
4. Complete the Simon pattern challenge
5. Return to the main room and solve the final binary lock
6. Escape before time runs out!

## Technologies Used

- [Three.js](https://threejs.org/) - 3D rendering engine
- [Tailwind CSS](https://tailwindcss.com/) - Responsive styling
- JavaScript - Game logic and interactions
- HTML5 - Game structure

## Setup and Installation

No installation required! The game runs directly in any modern web browser:

1. Open `index.html` in your browser
2. For best experience, use a mobile device or tablet
3. Alternatively, use Chrome/Firefox desktop with device emulation

## File Structure
rogue-ai-archive/
├── index.html # Main game file
├── README.md # This documentation
└── assets/ # (Optional directory for future assets)
├── textures/ # 3D texture files for future
├── sounds/ # Audio files for future
└── models/ # 3D model files for future


## Customization

You can modify these aspects of the game:

- **Timer duration**: Change `startTimer(30 * 60)` in the script
- **Puzzle difficulty**: Adjust level requirements in `puzzles` object
- **Colors**: Modify the CSS variables for a different visual style
- **Room design**: Edit the `createRoom1()` and `createRoom2()` functions

## Future Improvements

- Add sound effects and background music
- Implement more complex 3D models
- Create additional rooms and puzzles
- Add save/load functionality
- Implement leaderboards
- Add accessibility options

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

