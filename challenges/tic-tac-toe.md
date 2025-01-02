# 🎮 React Native Tic-Tac-Toe
Build a classic Tic-Tac-Toe game.

## 🎯 Overview
Create a React Native app that implements the classic Tic-Tac-Toe game. Focus on clean architecture, state management, and app navigation.

## ⭐ Features

### 🎯 Game Screen
- 🎰 3x3 interactive game grid [default]
- 🔄 Add dynamic grid size
- 🎲 Alternating player turns (X and O)
- 🏆 Win/Draw detection with status messages
- 🔄 Reset game functionality
- 🧭 Navigation to winner history

### 📜 History Screen
- 📊 List of past winners
- 💾 Persistent storage using AsyncStorage/MMKV

### ⚙️ Settings Modal
- 📏 Grid size selector options:
  - Preset sizes (3x3, 4x4, 5x5)
  - Custom input (min: 3x3, max: 10x10)
- 💾 Save preferences
- ❌ Close modal button

## 🛠️ Tech Stack

- **⚛️ React Native Cli or Expo**
- **📦 State Management** - Choice of:
  - Zustand
  - Jotai
  - Redux
  - MobX
  - Legend State
  - XState
  - Tanstack Query
- **💾 Storage** - Choice of:
  - AsyncStorage
  - MMKV
- **🧭 Navigation** - React Navigation or React Native Navigation
- **🧪 Testing** - Jest & React Native Testing Library
- **📝 TypeScript** - Type safety
- **📱 Responsive Design** - Flexbox & Dimensions API

## ✨ Key Features

- ✅ Clean, modular code architecture
- ✅ Unit testing with Jest & React Native Testing Library
- ✅ Responsive UI for all screen sizes
- ✅ Persistent game history
- ✅ App navigation with React Navigation or React Native Navigation
- ✅ State management implementation

Happy coding! 🚀 