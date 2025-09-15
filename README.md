
# ♟️ Chess Game  

A fully functional chess game built with **TypeScript**, featuring player vs. player gameplay, move validation, and a clean UI.  

---

## 📌 Project Overview  
This project implements the complete rules of chess, including valid moves, captures, check, and checkmate detection. It is designed to be simple, modular, and extendable for future improvements such as AI opponents or online multiplayer.  

---

## ✨ Features  
- Standard **8x8 chessboard** with all rules implemented.  
- Move validation (legal moves only).  
- Highlights possible moves for each piece.  
- Game end conditions: checkmate, stalemate, and draw.  
- Written in **TypeScript** for type safety and maintainability.  
- Modular structure (`api.ts`, `index.ts`) for scalability.  

---

## 📂 Project Structure  
```
chess-game/
├── src/
│   ├── api.ts       # Core game logic and utilities
│   ├── index.ts     # Entry point for running the game
├── public/          # Assets (if UI exists)
├── package.json     # Project dependencies
├── tsconfig.json    # TypeScript configuration
└── README.md        # Documentation
```

---

## ⚙️ Installation & Setup  
Clone the repository and install dependencies:  
```bash
git clone https://github.com/yourusername/chess-game.git
cd chess-game
npm install
```

Run the development server (if React/Next.js):  
```bash
npm run dev
```

Or compile and run directly (if Node.js only):  
```bash
tsc
node dist/index.js
```

---

## 🕹️ How to Play  
- Launch the game from the terminal or web app.  
- Select and move pieces by clicking/tapping.  
- Legal moves are highlighted.  
- Play until checkmate, stalemate, or draw.  

---

## 🛠️ Tech Stack  
- **Language**: TypeScript  
- **Framework**: Node.js / React / Next.js *(adjust based on your setup)*  
- **Build Tools**: npm, tsc  

---

## 🚀 Future Improvements  
- Add AI opponent (Minimax or Stockfish integration).  
- Add multiplayer mode with WebSockets.  
- Add game timer and move history.  

---

## 📜 License  
This project is licensed under the MIT License  

---

## 👤 Author  
Developed by **[Your Name]**  
Connect with me on [LinkedIn](https://linkedin.com) or check out more projects on [GitHub](https://github.com/yourusername).
