# Chess++

![Chess Banner] <img width="336" alt="Screenshot-2024-05-05-19-34-45 2024-05-09 at 23 12 52" src="https://github.com/CSC-3380-Spring-2024/ChessFinal/assets/118138523/784399cd-4ece-4bee-8b8c-aa361a1e1395">
)

Chess++, This C# WPF application brings you three thrilling game modes: Exploding Chess 💥, Horde Chess 🧟, and Chess960 🔀, ensuring your strategic prowess is put to the ultimate test.

## Features

- **Exploding Chess 💥**: Witness the board come alive as captured pieces explode in a spectacular display of fireworks! 🎆
- **Horde Chess 🧟**: Defend your kingdom against an endless horde of relentless chess pieces. Can you survive the onslaught? 💪
- **Chess960 🔀**: Embrace the chaos as the starting position of the pieces is randomized, putting your skills to the ultimate test! 🤯
- **Fen Notation 🗺️**: Create custom board setups with the power of Fen Notation, unleashing endless possibilities! 📝

## Installation

1. Clone the repository:
2. Navigate to the project directory:
3. Build the project: `dotnet build`
4. Run the application: `dotnet run`

## Usage

```csharp
// Example usage in C#
ChessGame game = new ChessGame();
game.StartNewGame(GameMode.ExplodingChess);
// Have fun and conquer the chessboard! 👑
