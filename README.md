# Tic-Tac-Toe Game 🎮

An interactive and beautifully designed Android Tic-Tac-Toe game application with a smooth user experience and engaging animations.

## 📱 About

This is a classic Tic-Tac-Toe game built for Android devices, featuring a clean interface, player name customization, and a delightful splash screen animation. Perfect for quick gaming sessions with friends!

## ✨ Features

- **Splash Screen**: Engaging animated splash screen with smooth transitions
- **Player Customization**: Enter custom names for both players before starting the game
- **Interactive Gameplay**: Classic 3x3 Tic-Tac-Toe grid with touch-based interaction
- **Turn Indicator**: Visual indication of whose turn it is with dynamic background changes
- **Win Detection**: Automatic winner detection for all possible winning combinations
- **Draw Detection**: Identifies when the game ends in a draw
- **Game Results Dialog**: Beautiful winner announcement dialog with options to:
  - Restart the game with the same players
  - Return to player selection screen
- **Responsive Layout**: Optimized layouts for different screen sizes (hdpi, mdpi, xhdpi, xxhdpi, xxxhdpi, large, xlarge, small, normal)
- **Portrait Lock**: Consistent portrait orientation throughout the app for better UX

## 🛠️ Technical Details

### Built With

- **Language**: Java
- **IDE**: Android Studio
- **Min SDK**: API 24 (Android 7.0 Nougat)
- **Target SDK**: API 33 (Android 13)
- **Compile SDK**: API 33

### Key Dependencies

- AndroidX AppCompat: 1.6.1
- Material Design Components: 1.5.0
- ConstraintLayout: 2.1.4
- SDP (Scalable Size Unit): 1.1.0
- SSP (Scalable Text Size): 1.1.0

### Project Structure

```
com.example.tictactoegame/
├── splash.java          # Splash screen activity with animations
├── AddPlayers.java      # Player name input screen
└── MainActivity.java    # Main game logic and UI
```

### Game Logic

- **Win Combinations**: Checks 8 possible winning combinations (3 rows, 3 columns, 2 diagonals)
- **Turn Management**: Alternates between Player 1 (X) and Player 2 (O)
- **Box Selection Validation**: Prevents selecting already filled boxes
- **Draw Condition**: Triggers when all 9 boxes are filled without a winner

## 📥 Download

### Latest Release: v1.0.0

Download the latest version of the app:

**[Download Tic-Tac-Toe.apk (v1.0.0)](https://github.com/RifatHossaiN47/Tic-Tac-Toe-Game/releases/download/v1.0.0/Tic-Tac-Toe.apk)**

Or visit the [Releases](https://github.com/RifatHossaiN47/Tic-Tac-Toe-Game/releases) page for all available versions.

## 🚀 Installation

1. Download the APK file from the releases section
2. Enable "Install from Unknown Sources" in your Android device settings
3. Open the downloaded APK file
4. Follow the installation prompts
5. Launch the app and enjoy!

## 🎯 How to Play

1. **Launch the app** - Watch the animated splash screen
2. **Enter player names** - Input names for both Player 1 and Player 2
3. **Start playing** - Player 1 (X) goes first, tap any empty box to make your move
4. **Take turns** - Watch for the highlighted player indicator showing whose turn it is
5. **Win or draw** - First player to get three in a row wins! If all boxes fill up without a winner, it's a draw
6. **Play again** - Choose to restart with the same players or change player names

## 🔧 Building from Source

### Prerequisites

- Android Studio (latest version recommended)
- JDK 8 or higher
- Android SDK with API level 33

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/RifatHossaiN47/Tic-Tac-Toe-Game.git
   ```
2. Open the project in Android Studio
3. Sync Gradle files
4. Run the project on an emulator or physical device

### Build APK

```bash
./gradlew assembleRelease
```

The APK will be generated in `app/build/outputs/apk/release/`

## 📸 Screenshots

_(Add screenshots of your app here to showcase the UI)_

## 🎨 UI/UX Highlights

- Custom drawables for X and O markers
- Smooth animations on splash screen
- Material Design components
- Scalable dimensions for consistent look across devices
- Intuitive color scheme with dynamic player highlighting

## 📄 License

This project is available for personal and educational use.

## 👨‍💻 Developer

**RifatHossaiN47**

- GitHub: [@RifatHossaiN47](https://github.com/RifatHossaiN47)

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/RifatHossaiN47/Tic-Tac-Toe-Game/issues).

## ⭐ Show Your Support

If you like this project, please consider giving it a ⭐ on GitHub!

---

**Version**: 1.0.0  
**Package**: com.example.tictactoegame  
**Last Updated**: December 2025
