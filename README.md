# KHAYBAR 🚀

**A strategic turn-based warfare game built with HTML5, CSS3, and JavaScript**

[![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen)](https://PyAIM.github.io/khaybar/)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

## 🎮 Play Now

**[▶️ Play KHAYBAR Online](https://PyAIM.github.io/khaybar/)**

## 📖 About

KHAYBAR is an intense strategic warfare game where two cities - FARES and ZOHON - battle for supremacy. Each city has unique weapons and abilities, requiring tactical thinking and resource management to achieve victory.

### ⚡ Key Features

- **Turn-based Strategy**: Plan your attacks and defenses carefully
- **Unique Arsenals**: Each faction has specialized weapons and capabilities
- **AI Opponent**: Challenge the computer or play with friends
- **Dynamic Audio**: Immersive sound effects and background music
- **Real-time Effects**: Explosive visual feedback and animations
- **Bonus System**: Collect random token drops during battle

## 🎯 How to Play

### Objective
Destroy your opponent's city or have higher health when the 2-minute timer runs out. First to win 3 rounds wins the match!

### Game Flow
1. **Purchase Phase**: Buy up to 3 weapons per turn (max 2 offensive)
2. **Attack Phase**: Launch your arsenal or end turn strategically
3. **Defense**: Use interceptor systems to protect your city

### Victory Conditions
- **Instant Win**: Reduce opponent's health to 0
- **Timer Victory**: Higher health wins when time expires
- **Tiebreaker**: Most tokens wins if health is tied

## ⚔️ Factions & Weapons

### 🔴 FARES (Red Team)
- **Standard Missile** (100 tokens): 20 damage, interceptable
- **Hypersonic Missile** (250 tokens): 30 damage, uninterceptable
- **Air Defense** (180 tokens): Intercepts bombers and drones

### 🔵 ZOHON (Blue Team)  
- **Bomber** (200 tokens): 25 damage, interceptable
- **GHOST Bomber** (320 tokens): 35 damage, stealth technology
- **Missile Defense** (220 tokens): Intercepts missiles and drones

### 🛠️ Shared Arsenal
- **Attack Drone** (150 tokens): 15 damage, versatile
- **Repair** (50 tokens/10HP): Restore city health

## ⌨️ Controls

| Key | Action |
|-----|--------|
| `1-8` | Purchase weapons |
| `SPACE` | Launch attack |
| `ENTER` | End turn |
| `M` | Toggle music |
| `S` | Toggle sound effects |
| `H` | Show/hide instructions |
| `ESC` | Close menus |

## 🤖 AI Mode

Toggle "VS AI: ON" to face an intelligent computer opponent that:
- Analyzes battlefield conditions
- Makes strategic purchasing decisions
- Adapts tactics based on health and resources
- Provides varying difficulty levels

## 🛠️ Technical Details

### Built With
- **HTML5** - Game structure and interface
- **CSS3** - Styling, animations, and visual effects
- **JavaScript** - Game logic, AI, and interactivity
- **Web Audio API** - Sound effects and music system

### Browser Compatibility
- ✅ Chrome 80+
- ✅ Firefox 75+
- ✅ Safari 13+
- ✅ Edge 80+
- 📱 Mobile browsers supported

### Audio Files Required
music/
├── menu.mp3          # Main menu background music
├── battleThemeA.mp3  # In-game battle music
└── gameover.mp3      # Victory/defeat music

## 🚀 Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/PyAIM/khaybar.git
   cd khaybar

Add music files

Place your MP3 files in the music/ directory
Ensure filenames match exactly: menu.mp3, battleThemeA.mp3, gameover.mp3


Open in browser
bash# Simple HTTP server (Python 3)
python -m http.server 8000

# Or use Live Server extension in VS Code

Navigate to http://localhost:8000

🎵 Audio Credits
https://opengameart.org/

👨‍💻 Development
Created by: M. Ben-Azzouz
AI Assistant: Claude Sonnet 4 (Anthropic)
Repository: GitHub

📄 License
This project is licensed under the MIT License - see the LICENSE file for details.
🤝 Contributing
Contributions, issues, and feature requests are welcome! Feel free to check the issues page.
⭐ Show Your Support
Give a ⭐ if you enjoyed playing KHAYBAR!

Ready for battle? 🎮 Play KHAYBAR Now!
