# Shafrah

Shafrah is a real-time multiplayer social game built with SwiftUI and Firebase Realtime Database. Players compete through strategy, communication, and word-guessing mechanics in a fast-paced competitive experience.

## Features

- Real-time multiplayer synchronization using Firebase Realtime Database
- 4-player team mode (Red Team vs Blue Team)
- Competitive 2-player mode with alternating spy and agent roles
- 4-digit room code system for quick matchmaking
- Black-word elimination mechanic
- Optional in-game timer for added challenge
- Arabic RTL interface with Amiri font support
- Confetti victory animations using SPConfetti
- Smooth and responsive SwiftUI user interface

## Technologies Used

| Technology | Purpose |
|------------|---------|
| SwiftUI | User Interface Development |
| Firebase Realtime Database | Real-time Multiplayer Synchronization |
| MVVM Architecture | Application Structure & State Management |
| SPConfetti | Win Animations |
| Git & GitHub | Version Control |

## Multiplayer System

Shafrah uses Firebase Realtime Database to synchronize gameplay instantly between players without requiring authentication.

### How It Works
1. A player creates a room
2. A unique 4-digit room code is generated
3. Other players join using the same room code
4. Game state updates are synchronized in real time across all devices

## Project Structure

```plaintext
Shafrah/
├── Models/
│   ├── Card.swift
│   ├── Team.swift
│   └── GameSettings.swift
├── ViewModels/
│   ├── GameViewModel.swift
│   └── RoomViewModel.swift
├── Views/
│   ├── GameView.swift
│   ├── HomeView.swift
│   ├── CreateRoomView.swift
│   ├── JoinRoomView.swift
│   └── OnboardingView.swift
├── Services/
│   └── FirebaseManager.swift
└── Resources/
    └── ArabicWords.swift

## Developer
Wasan Hamoud

📧 wasan5hm5@icloud.com    
🔗 [Support Page](https://www.notion.so/Shafrah-Support-3374593e1cc8801dba6cf85bd2a92ca1)

---

## License

This project is private and all rights are reserved © 2026 Wasan Hamoud
