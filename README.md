# Card Game Engine — Fishing Card Game (C# / .NET)

Academic project developed in C# demonstrating **advanced object-oriented programming** and **clean software architecture**.

This project implements a **Fishing Card Game engine** with extensible rules and player behaviors using proven design patterns.

## Key Concepts

- Object-Oriented Programming (interfaces, inheritance, polymorphism)
- **Strategy Pattern** for player decision logic
- **Observer Pattern** for game event notifications
- Delegates for flexible and decoupled behavior
- Turn-based game engine design

## Features

- Deck, cards, players and hands management
- Rule-based game flow (turns, draws, plays)
- Strategy-based player behavior (easily extendable)
- Event-driven notifications during gameplay
- Console-based execution (logic-focused)

## Tech Stack

- C# / .NET
- Console Application
- Object-Oriented Programming (OOP)
- Design Patterns (Strategy, Observer)
- Clean Architecture principles

## Project Structure

```
csharp-card-game-engine/
├─ src/
│ └─ FishingCardGame/
│ ├─ FishingCardGame.csproj
│ ├─ Program.cs
│ 
└─ README.md

## How to Run

### Using Visual Studio
1. Open Visual Studio
2. Select **Open a project or solution**
3. Navigate to `src/FishingCardGame` and open the `FishingCardGame.csproj` file
4. Run the application


### Using .NET CLI
```bash
cd src/FishingCardGame
dotnet restore
dotnet run
```

## Notes

This project focuses on **software design, extensibility, and code quality** rather than graphical interface.
