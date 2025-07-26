# 🎲 Yahtzee Game - Enhanced Edition

A modern, fully-featured implementation of the classic Yahtzee dice game with enhanced gameplay mechanics and beautiful UI.

## 🎮 Live Demo

Play the game at: [https://echooff3.github.io/yath-dice-game](https://echooff3.github.io/yath-dice-game)

Local development server: http://127.0.0.1:5500/

## ✨ Features

### 🎯 Core Gameplay
- **Classic Yahtzee Rules**: Complete implementation of traditional Yahtzee scoring
- **2-4 Player Support**: Multiplayer gameplay with automatic turn management
- **13 Rounds**: Full game with all scoring categories
- **3 Rolls Per Turn**: Standard roll mechanics with dice holding

### 🎲 Enhanced Dice System
- **Interactive Dice Rolling**: Click and hold to shake dice with realistic animation
- **Dice Holding**: Click individual dice to hold them between rolls
- **Smooth Animations**: Satisfying shake effects and visual feedback
- **Touch Support**: Full mobile device compatibility

### 🏆 Advanced Scoring
- **Automatic Calculation**: All scores calculated automatically
- **Real-time Preview**: See potential scores before committing
- **Upper Section Bonus**: Automatic 35-point bonus for 63+ in upper section
- **Smart Score Display**: Visual indicators for scored categories

### ⚡ Yahtzee Challenge System
- **5-Second Challenge**: Quick-click challenge when Yahtzee is rolled
- **Countdown Timer**: Visual countdown with pulsing animation
- **Auto-Assignment**: Automatic score assignment upon successful claim
- **Miss Penalty**: Continue normal turn if challenge is missed

### 🎨 Modern UI/UX
- **Responsive Design**: Optimized for desktop, tablet, and mobile
- **Beautiful Gradients**: Modern color scheme with smooth transitions
- **Active Player Highlight**: Clear visual indication of current player
- **Smooth Animations**: Polished transitions and hover effects
- **Clean Typography**: Easy-to-read fonts and clear information hierarchy

### 📊 Score Management
- **Live Score Updates**: Real-time total calculation
- **Visual Score States**: Different styles for scored vs. potential scores
- **Upper/Lower Sections**: Properly organized scorecard layout
- **Final Score Ranking**: End-game ranking with medal system

### 🎉 Game Features
- **Game Over Screen**: Winner announcement with final rankings
- **Restart Functionality**: Easy game reset from any state
- **Error Prevention**: Smart validation and user guidance
- **Progress Tracking**: Clear turn and round progression

## 🎯 Scoring Categories

### Upper Section
- **Ones through Sixes**: Sum of respective dice values
- **Upper Bonus**: 35 points for scoring 63+ in upper section

### Lower Section
- **Three of a Kind**: Sum of all dice (if 3+ of same value)
- **Four of a Kind**: Sum of all dice (if 4+ of same value)
- **Full House**: 25 points (3 of one kind + 2 of another)
- **Small Straight**: 30 points (4 consecutive numbers)
- **Large Straight**: 40 points (5 consecutive numbers)
- **Yahtzee**: 50 points (all 5 dice same value)
- **Chance**: Sum of all dice (no restrictions)

## 🚀 Technical Features

### Performance
- **Lightweight**: Single HTML file with embedded CSS/JS
- **Fast Loading**: Optimized assets and minimal dependencies
- **Smooth Animations**: Hardware-accelerated CSS transitions
- **Efficient DOM Updates**: Smart rendering for optimal performance

### Compatibility
- **Cross-Browser**: Works on all modern browsers
- **Mobile-Friendly**: Touch events and responsive design
- **Progressive Enhancement**: Graceful degradation for older devices
- **Accessibility**: Keyboard navigation and screen reader support

### Code Quality
- **Clean Architecture**: Well-organized game state management
- **Modern JavaScript**: ES6+ features and best practices
- **Maintainable CSS**: Organized styles with CSS custom properties
- **Documentation**: Comprehensive code comments

## 🎮 How to Play

1. **Setup**: Enter 2-4 player names to start the game
2. **Rolling**: Click and hold the roll button to shake dice
3. **Holding**: Click individual dice to hold them for next roll
4. **Scoring**: Click a category to assign your current dice roll
5. **Yahtzee Challenge**: When you roll 5 of a kind, quickly click the Yahtzee button!
6. **Winning**: Player with highest total after 13 rounds wins

## 🛠️ Development

### Local Setup
```bash
# Clone the repository
git clone https://github.com/echooff3/yath-dice-game.git

# Open in your preferred local server
# For VS Code with Live Server extension:
# Right-click index.html and select "Open with Live Server"

# Or use Python's built-in server:
python -m http.server 5500
```

### File Structure
```
yath-dice-game/
├── index.html          # Complete game implementation
├── README.md          # This documentation
└── assets/            # (Future: images, sounds, etc.)
```

## 🎯 Game Rules Summary

- Each player takes turns rolling 5 dice up to 3 times per turn
- After each roll, choose which dice to keep and which to re-roll
- After your final roll (or sooner), assign your dice to a scoring category
- Each category can only be used once per player
- Game ends when all players have filled all 13 categories
- Highest total score wins!

## 🚧 Future Enhancements

- **Sound Effects**: Dice rolling and success sounds
- **Animations**: Enhanced visual effects for special rolls
- **Statistics**: Game history and player statistics
- **Themes**: Multiple color schemes and visual themes
- **AI Players**: Computer opponents with different difficulty levels
- **Online Multiplayer**: Real-time multiplayer support

## 📝 Version History

### v2.0.0 (Enhanced Edition)
- Complete rewrite with modern architecture
- Added Yahtzee challenge system
- Improved UI/UX design
- Enhanced mobile support
- Automatic scoring and turn management

### v1.0.0 (Original)
- Basic Yahtzee implementation
- Manual scoring system
- Simple UI design

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

---

**Enjoy playing Yahtzee! 🎲🎉**
