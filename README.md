# Space Invaders - Pygame

A classic arcade-style Space Invaders game built with Python and Pygame. Defend your spaceship against waves of alien enemies in this nostalgic recreation of the iconic 1978 game.

![Space Invaders Game](https://img.shields.io/badge/Python-3.x-blue.svg) ![Pygame](https://img.shields.io/badge/Pygame-2.0+-green.svg) 

## 🎮 Game Features

- **Classic Gameplay**: Move left and right to dodge enemies and shoot bullets
- **Multiple Enemies**: Battle against 6 enemies with intelligent movement patterns
- **Collision Detection**: Precise collision system for bullets and enemies
- **Score System**: Track your progress with an integrated scoring system
- **Game Over Screen**: Clear end-game feedback when enemies reach your position
- **Sound Effects**: Immersive audio with laser sounds and explosion effects
- **Smooth Controls**: Responsive keyboard controls for optimal gameplay

## 🚀 Getting Started

### Prerequisites

- Python 3.x
- Pygame library

### Installation

1. **Clone the repository:**
  git clone https://github.com/ojas-03/Space-Invaders-Pygame-.git
  cd Space-Invaders-Pygame-

2. **Install the required dependencies:**
   pip install pygame

3. **Add the required asset files to your project directory:**
- `background.png` - Game background image
- `player.png` - Player spaceship sprite
- `enemy.png` - Enemy alien sprite
- `bullet.png` - Bullet sprite
- `ufo.png` - Game icon
- `laser.wav` - Bullet firing sound effect
- `explosion.wav` - Enemy destruction sound effect

### Running the Game
  python main.py
  
## 🎯 How to Play

| Control | Action |
|---------|--------|
| ← Left Arrow | Move spaceship left |
| → Right Arrow | Move spaceship right |
| Spacebar | Fire bullets |

### Objective
- Shoot all enemies before they reach your position
- Game ends when any enemy reaches the bottom of the screen
- Earn points for each enemy destroyed

## 🛠️ Technical Details

- **Resolution**: 800x600 pixels
- **Enemy Count**: 6 enemies with randomized starting positions
- **Collision Distance**: 27 pixels for precise hit detection
- **Player Boundaries**: Movement restricted between 0-736 pixels

## 📁 Project Structure

Space-Invaders-Pygame-/
├── main.py # Main game file
├── assets/ # Game assets (create this folder)
│ ├── background.png # Background image
│ ├── player.png # Player sprite
│ ├── enemy.png # Enemy sprite
│ ├── bullet.png # Bullet sprite
│ ├── ufo.png # Game icon
│ ├── laser.wav # Shooting sound
│ └── explosion.wav # Explosion sound
└── README.md # Project documentation

## 🎨 Game Mechanics

### Enemy Behavior
- Enemies move horizontally across the screen
- When reaching screen edges, enemies drop down and change direction
- Game over triggers when enemies reach Y position > 440

### Collision System
- Uses Euclidean distance formula for precise collision detection
- Collision threshold: 27 pixels between bullet and enemy centers

### Bullet System
- Single bullet system with "ready" and "fire" states
- Bullet resets when reaching top of screen or hitting an enemy

## 🔧 Customization Options

Easily modify these variables in `main.py`:
num_of_enemies = 6 # Number of enemies
playerX_change = 5 # Player movement speed
enemyX_change = # Enemy horizontal speed range
bulletY_change = 5 # Bullet speed
enemyY_change = 20 # Enemy drop distance

## 🐛 Known Issues & Future Enhancements

### Current Limitations
- Single bullet at a time
- No multiple lives system
- No increasing difficulty levels

### Planned Features
- [ ] Multiple bullets
- [ ] Power-ups and special weapons
- [ ] Multiple levels with increasing difficulty
- [ ] High score persistence
- [ ] Background music integration

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch**
  git checkout -b feature/AmazingFeature
3. **Commit your changes**
  git commit -m 'Add some AmazingFeature'
4. **Push to the branch**
  git push origin feature/AmazingFeature
5. **Open a Pull Request**

## 📋 Requirements

Create a `requirements.txt` file:
  pygame>=2.0.0

**Missing asset files error**
- Ensure all image and sound files are in the same directory as `main.py`
- Check file names match exactly (case-sensitive)

**Sound not working**
- Verify audio files are in correct format (.wav)
- Check system audio settings

## 👨‍💻 Author

**Ojas** - [@ojas-03](https://github.com/ojas-03)

## 🎖️ Acknowledgments

- Inspired by the classic **Space Invaders** arcade game by Tomohiro Nishikado
- Built with the powerful **Pygame** library
- Thanks to the Python gaming community for resources and inspiration

## ⭐ Show Your Support

Give this project a ⭐ if you found it helpful!

---

**Ready to defend Earth? Let the space battle begin! 🚀👾**


