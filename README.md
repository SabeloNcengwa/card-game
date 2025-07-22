# Higher or Lower Card Game

A modern, interactive web-based card game where players predict whether the next card will be higher or lower than the current one. Built with pure HTML, CSS, and JavaScript.

## 🎮 Game Overview

**Higher or Lower** is a classic guessing game that tests your luck and intuition. Players are shown a card and must predict whether the next card drawn will have a higher or lower value. The game continues until you make an incorrect guess.

## 🎯 How to Play

1. **Start the Game**: Click either "Higher" or "Lower" to begin
2. **Make Your Prediction**: Based on the current card shown, guess if the next card will be:
   - **Higher**: Next card value ≥ current card value
   - **Lower**: Next card value ≤ current card value
3. **Score Points**: Earn 10 points for each correct guess
4. **Build Streaks**: Try to get as many correct guesses in a row as possible
5. **Game Over**: One wrong guess ends the game
6. **New Game**: Click "New Game" to restart anytime

## 🃏 Card Values

- **Ace (A)**: Value 1 (lowest)
- **Number Cards**: 2-10 (face value)
- **Jack (J)**: Value 11
- **Queen (Q)**: Value 12  
- **King (K)**: Value 13 (highest)

## ✨ Features

### 🎨 Modern Design
- **Glassmorphism UI**: Translucent panels with backdrop blur effects
- **Gradient Backgrounds**: Beautiful color transitions
- **Smooth Animations**: Card flip animations and hover effects
- **Responsive Layout**: Works perfectly on desktop and mobile devices

### 🎯 Gameplay Features
- **Full 52-Card Deck**: Complete standard deck with proper shuffling
- **Real-time Scoring**: Live score updates with visual feedback
- **Streak Tracking**: Monitor your current winning streak
- **Best Score Memory**: Your high score is saved locally in your browser
- **Automatic Deck Management**: Deck reshuffles when cards run out

### 🎪 Visual Effects
- **Card Flip Animation**: Realistic 3D flip when cards are revealed
- **Color-coded Suits**: Red hearts/diamonds, black spades/clubs
- **Interactive Buttons**: Hover effects and visual feedback
- **Result Messages**: Clear feedback for correct/incorrect guesses

## 🛠️ Technical Details

### Technologies Used
- **HTML5**: Semantic structure and layout
- **CSS3**: Modern styling with flexbox, animations, and gradients
- **JavaScript (ES6+)**: Game logic, DOM manipulation, and local storage

### Browser Compatibility
- Chrome/Edge 60+
- Firefox 55+
- Safari 12+
- Mobile browsers (iOS Safari, Android Chrome)

### Performance
- **Lightweight**: No external dependencies or frameworks
- **Fast Loading**: All assets inline, no network requests
- **Memory Efficient**: Automatic deck management prevents memory leaks

## 📁 File Structure

```
card-game.html          # Complete game in single HTML file
├── HTML structure      # Game layout and elements
├── CSS styles         # All styling and animations
└── JavaScript logic   # Game mechanics and interactions
```

## 🚀 Getting Started

### Option 1: Direct Download
1. Save the HTML file to your computer
2. Open the file in any modern web browser
3. Start playing immediately!

### Option 2: Local Server
```bash
# If you prefer to run on a local server
python -m http.server 8000
# or
npx serve .
```

## 🎲 Game Statistics

The game tracks several metrics:
- **Current Score**: Points earned in the current game
- **Best Score**: Highest score achieved (stored locally)
- **Current Streak**: Consecutive correct guesses
- **Win Rate**: Track your success over time

## 🎨 Customization

The game is built with modular CSS and JavaScript, making it easy to customize:

### Styling
- Modify colors in the CSS gradient variables
- Adjust card dimensions in the `.card` class
- Change animations in the `@keyframes` sections

### Game Logic
- Adjust scoring in the `makeGuess()` method
- Modify card values in the `values` array
- Add new game modes by extending the `CardGame` class

## 🐛 Known Issues & Limitations

- Scores are stored locally and won't sync across devices
- Game requires JavaScript enabled
- Cards are shuffled randomly each deck refresh

## 🚀 Future Enhancements

Potential improvements for future versions:
- Multiple difficulty levels
- Sound effects and music
- Multiplayer mode
- Achievement system
- Card counting hints
- Tournament mode

## 📄 License

This project is open source and available under the MIT License. Feel free to use, modify, and distribute as needed.

## 🤝 Contributing

This is a standalone HTML file perfect for:
- Educational purposes
- Code learning and modification
- Portfolio projects
- Quick entertainment

## 🎊 Enjoy Playing!

Test your intuition, build impressive streaks, and see how high you can score! The game combines luck with psychological elements as you develop your own strategies for predicting card sequences.

---

*Built with ❤️ using vanilla web technologies*
