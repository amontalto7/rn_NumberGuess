# 🎮 React Native Guessing Game App

A mobile number guessing game built with **React Native** and **Expo**. The app allows users to pick a number, and the system will try to guess it through interactive rounds.

Course: https://www.udemy.com/course/react-native-the-practical-guide/

---

## 🚀 Features

- Clean and responsive UI with **LinearGradient backgrounds**
- Custom fonts using **expo-font**
- Three main game screens:
  - `StartGameScreen`: User picks a number
  - `GameScreen`: App attempts to guess the number
  - `GameOverScreen`: Summary of rounds and option to restart
- Image background with layered styling
- Game logic controlled via React state hooks
- Splash screen until custom fonts are loaded

---

## 🧠 Technologies Used

- **React Native** (Functional Components with Hooks)
- **Expo** (for fonts, image background, status bar, etc.)
- **Custom Fonts** (OpenSans-Regular & OpenSans-Bold)
- **Expo AppLoading** (for smooth font loading experience)
- **SafeAreaView** (to ensure proper rendering across devices)

---

## 📂 Project Structure

📦 your-app ├── 📁 assets │ ├── 📁 fonts │ │ ├── OpenSans-Regular.ttf │ │ └── OpenSans-Bold.ttf │ └── 📁 images │ └── background.png ├── 📁 constants │ └── colors.js ├── 📁 screens │ ├── StartGameScreen.js │ ├── GameScreen.js │ └── GameOverScreen.js ├── App.js └── README.md


---

## 📲 Running the App

### 1. Clone the repo

2. Install dependencies
bash
Copy
Edit
npm install
# or
yarn install

3. Run the project
bash
Copy
Edit
npx expo start
Scan the QR code with your Expo Go app or run on an emulator.