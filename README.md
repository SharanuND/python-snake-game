# Python Snake Game 🐍

A classic Snake game implementation using Python and Pygame. This project features a modern, clean implementation of the timeless Snake game with smooth controls and a user-friendly interface.

## 🎮 Features

- Classic snake gameplay mechanics
- Smooth controls using arrow keys
- Score tracking
- Game over screen with restart option
- Clean, modern implementation
- Responsive window size (600x600 pixels)

## 🚀 Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/python-snake-game.git
cd python-snake-game
```

2. Install the required dependencies:
```bash
pip install -r requirements.txt
```

## 🎯 How to Play

1. Run the game:
```bash
python snake_game.py
```

2. Controls:
   - Use arrow keys to control the snake's direction
   - ↑ (Up arrow): Move up
   - ↓ (Down arrow): Move down
   - ← (Left arrow): Move left
   - → (Right arrow): Move right
   - Press 'R' to restart when game is over

3. Game Rules:
   - Eat the red food squares to grow and increase your score
   - Avoid hitting the walls or the snake's own body
   - Try to get the highest score possible!

## 🛠️ Project Structure

```
python-snake-game/
├── snake_game.py      # Main game implementation
├── requirements.txt   # Project dependencies
└── README.md         # Project documentation
```

## 🎨 Customization

The game can be easily customized by modifying the following constants in `snake_game.py`:
- `WINDOW_SIZE`: Change the window size (default: 600)
- `GRID_SIZE`: Adjust the grid cell size (default: 20)
- `FPS`: Modify the game speed (default: 10)
- Colors: Customize the game's color scheme

## 🤝 Contributing

Contributions are welcome! Feel free to:
1. Fork the repository
2. Create a new branch
3. Make your changes
4. Submit a pull request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👏 Acknowledgments

- Built with [Pygame](https://www.pygame.org/)
- Inspired by the classic Snake game 