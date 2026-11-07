# 🎮 ValoGuess

> A real-time multiplayer Valorant guessing game.

[Play Now](https://valoguess.fun) ·
[Web App](https://github.com/valoguess/valoguess) ·
[Socket Server](https://github.com/valoguess/valoguess-socket-server)

![Gameplay screenshot](https://valoguess.fun/showcase/game.webp)

## 🎯 What is ValoGuess?

ValoGuess is a real-time 1v1 tactical deduction web game inspired by the classic "Guess Who?", adapted for the Valorant universe. Two players face off on an interactive board of 29 Valorant agents (excluding Hush, the new agent), ask targeted questions to eliminate possibilities, and race to deduce the opponent's secret agent.

## ✨ Features

- Real-time multiplayer matches
- Party creation and friend invites
- Live game-state synchronization
- Player profiles and friends
- Game history

## 🛠️ Built With

Next.js · TypeScript · Socket.IO · Redis · PostgreSQL · Drizzle

## 🏗️ Architecture

ValoGuess consists of two applications:

- [Web app](https://github.com/valoguess/valoguess) — UI, authentication, and persistent data
- [Socket server](https://github.com/valoguess/valoguess-socket-server) — real-time communication and game state

See each repository's README for technical details.

## 🤝 Contributing

Issues, ideas, and pull requests are welcome.
