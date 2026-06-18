# ♟️ Pawn Chess

A strategic chess variant where the goal is to **escape 2 pieces** through the opponent's baseline. Every piece moves only **1 square at a time**, creating a completely new tactical experience!

## 🎮 Play Now

Play directly in your browser: [Pawn Chess](https://lyre-bard.github.io/pawn-chess/)

Or download `index.html` and open it locally in any web browser.

## 📋 Game Features

✅ **Fully Playable** - Complete game mechanics implemented  
✅ **Undo Button** - Take back your last move  
✅ **Reset Game** - Start a new match instantly  
✅ **Move History Log** - Real-time action log displayed in sidebar  
✅ **Built-in Rules Modal** - Click "Show Rules" for game instructions  
✅ **Mobile Responsive** - Works on desktop, tablet, and mobile  
✅ **No Dependencies** - Pure HTML/CSS/JavaScript, no external libraries  

## 🎯 How to Play

### Objective
Be the first player to safely escape **2 pieces** through the opponent's baseline.

### Basic Rules

**Movement**: Every piece moves exactly **1 square** at a time.

**Pawns** 
- Move straight forward 1 square
- Attack diagonally (like standard chess)
- Can move 2 squares on their very first move (from starting position)
- When frontally blocked by an enemy pawn, can move diagonally to escape

**Backline Pieces (R, N, B, Q, K)**
- Move 1 square diagonally only
- Color-locked to their initial square type (white/black)
- Can only move forward on diagonals matching their color
- Attack straight ahead against specific opponents:
  - **Rooks** (R): Capture enemy Rooks straight ahead
  - **Knights** (N): Capture enemy Knights straight ahead
  - **Bishops** (B): Capture enemy Bishops straight ahead
  - **Queens** (Q): Capture any backline piece (R, N, B, Q) straight ahead
  - **Kings** (K): Capture Queens and Kings straight ahead
- When capturing, pieces shift to the new square's color property

### Escape Zones
- **P1 (Black)**: Escape through row 8 (bottom)
- **P2 (White)**: Escape through row 1 (top)

## 🎮 Controls

| Button | Action |
|--------|--------|
| 📜 Show Rules | Display game rules and mechanics |
| ↩️ Undo | Take back your last move |
| 🔄 Reset | Start a new game |
| Click cell | Select/move pieces |

## 🖼️ Board Layout

```
8 ♜ ♞ ♝ ♛ ♚ ♝ ♞ ♜   (P1 - Black backline)
7 ♟ · ♟ · ♟ · ♟ ·   (P1 - Pawns row 1)
6 · ♟ · ♟ · ♟ · ♟   (P1 - Pawns row 2)
5 · · · · · · · ·
4 · · · · · · · ·
3 ♙ · ♙ · ♙ · ♙ ·   (P2 - Pawns row 1)
2 · ♙ · ♙ · ♙ · ♙   (P2 - Pawns row 2)
1 ♖ ♘ ♗ ♕ ♔ ♗ ♘ ♖   (P2 - White backline)
  A B C D E F G H
```

## 🔧 Technical Details

- **Language**: Pure HTML5, CSS3, JavaScript (ES6)
- **Size**: Single `index.html` file (~15KB)
- **Compatibility**: All modern browsers (Chrome, Firefox, Safari, Edge)
- **No Build Tools**: Works immediately, no installation needed

## 📝 License

MIT License - Feel free to use, modify, and distribute!

See [LICENSE](LICENSE) for details.

## 🚀 Future Roadmap

- [ ] AI opponent (Easy/Hard difficulty)
- [ ] Online multiplayer support
- [ ] Game statistics & ELO rating
- [ ] Different board sizes (6x6, 10x10)
- [ ] Sound effects & animations
- [ ] Dark mode theme
- [ ] Save/load game feature
- [ ] Replay mode

## 💡 Contributing

Have ideas? Found a bug? Want to improve the game?

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Make your changes
4. Commit your work (`git commit -m 'Add amazing feature'`)
5. Push to the branch (`git push origin feature/amazing-feature`)
6. Open a Pull Request

## 📧 Contact & Feedback

Have feedback or suggestions? Feel free to [open an issue](https://github.com/lyre-bard/pawn-chess/issues) on GitHub!

---

**Made with ♟️ by the Pawn Chess Community**