# 🎲 Pig Game

A fun and interactive two-player dice game built with vanilla JavaScript.

## Game Description

Pig Game is a simple dice game where two players take turns rolling a die to accumulate points. The first player to reach 100 points wins the game.

## 🎮 Game Rules

1. The game has 2 players, playing in rounds
2. Each turn, a player rolls a dice as many times as they wish. Each result gets added to their CURRENT score
3. BUT, if the player rolls a 1, all their CURRENT score is lost. After that, it's the next player's turn
4. The player can choose to 'Hold', which means that their CURRENT score gets added to their TOTAL score. After that, it's the next player's turn
5. The first player to reach 100 points in their TOTAL score wins the game

## 🛠️ Technologies Used

- HTML5
- CSS3
- Vanilla JavaScript
- Google Fonts (Nunito)

## 🎯 Features

- Dynamic dice rolling animation
- Score tracking for both players
- Current score and total score display
- Responsive design
- Interactive UI with visual feedback
- Game state management
- Winner highlighting
- New game reset functionality

## 🚀 Setup and Usage

1. Clone the repository:
```bash
git clone https://github.com/your-username/pig-game.git
```

2. Open `index.html` in your browser

3. Start playing:
   - Click '🎲 Roll dice' to roll
   - Click '📥 Hold' to keep your current score
   - Click '🔄 New game' to start over

## 📁 Project Structure

```
pig-game/
├── index.html
├── style.css
├── script.js
├── dice-1.png
├── dice-2.png
├── dice-3.png
├── dice-4.png
├── dice-5.png
├── dice-6.png
└── README.md
```

## 🎨 Design Features

- Glass-morphism UI design
- Gradient background
- Smooth transitions and animations
- Responsive layout
- Clear visual feedback for active player
- Winner state styling

## 🔧 Technical Implementation

### JavaScript Features
- ES6+ syntax
- DOM manipulation
- Event handling
- State management
- Modular functions
- Clean code principles

### CSS Features
- Flexbox layout
- CSS transitions
- Custom properties
- Backdrop filters
- Box shadows
- Responsive design

## 🔄 Game Flow

1. Page loads with Player 1 active
2. Active player can:
   - Roll dice (accumulates points)
   - Hold (saves points)
   - Reset game
3. If player rolls 1:
   - Loses current score
   - Turn switches to other player
4. If player holds:
   - Current score adds to total
   - Turn switches to other player
5. First to 100 points wins

## 🎯 Future Enhancements

- Add sound effects
- Implement local storage for game state
- Add multiplayer support
- Create different difficulty levels
- Add customizable winning score
- Include player statistics
- Add mobile touch support
- Implement AI opponent

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



This project is open source and available under the [MIT License](LICENSE).

