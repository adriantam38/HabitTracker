# 📅 Habit Tracker App

A mobile habit tracking app built with **React Native**, **Expo**, **Appwrite**, and **NativeWind (TailwindCSS)**. This project was built as a personal milestone to deepen my understanding of full-stack mobile development.

---

## 📋 Table of Contents

- [About the Project](#about-the-project)
- [Tech Stack](#tech-stack)
- [Features](#features)
- [Getting Started](#getting-started)
- [Environment Variables](#environment-variables)
- [Acknowledgements](#acknowledgements)

---

## 🚀 About the Project

This is a personal milestone project — a fully functional **Habit Tracker** mobile app where users can create habits, mark them as complete, track their streaks, and manage their account. It uses Appwrite as a real-time backend and Expo to run on both iOS and Android.

---

## ⚙️ Tech Stack

| Technology                                              | Purpose                            |
| ------------------------------------------------------- | ---------------------------------- |
| [React Native](https://reactnative.dev/)                | Cross-platform mobile UI           |
| [Expo](https://expo.dev/)                               | Dev tooling & build platform       |
| [Appwrite](https://appwrite.io/)                        | Backend, auth & real-time database |
| [NativeWind / TailwindCSS](https://www.nativewind.dev/) | Utility-first styling              |
| [TypeScript](https://www.typescriptlang.org/)           | Type safety                        |
| React Hooks                                             | State & side-effect management     |

---

## ✨ Features

- 🏅 **Habit Streaks** — Visualise your daily streaks in real time
- ✅ **Add / Complete / Delete Habits** — Full CRUD habit management
- 🔄 **Real-Time Sync** — Data synced live via Appwrite
- 🌑 **Dark Mode** — Sleek dark UI powered by TailwindCSS
- 📱 **Responsive Design** — Mobile-first layout via Expo
- 🔐 **User Authentication** — Sign up, sign in, and session management with Appwrite Auth

---

## 🛠️ Getting Started

### Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/)
- [Expo CLI](https://docs.expo.dev/get-started/installation/)
- An [Appwrite](https://appwrite.io/) account and project

### Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/habit-tracker-react-native.git

# Navigate into the project directory
cd habit-tracker-react-native

# Install dependencies
npm install

# Start the development server
npx expo start
```

Scan the QR code with the **Expo Go** app on your phone, or press `i` / `a` to open in an iOS or Android simulator.

---

## 🔑 Environment Variables

Create a `.env` file in the root of your project and add your Appwrite credentials:

```env
EXPO_PUBLIC_APPWRITE_ENDPOINT=https://cloud.appwrite.io/v1
EXPO_PUBLIC_APPWRITE_PROJECT_ID=your_project_id
EXPO_PUBLIC_APPWRITE_DATABASE_ID=your_database_id
EXPO_PUBLIC_APPWRITE_HABITS_COLLECTION_ID=your_habits_collection_id
EXPO_PUBLIC_APPWRITE_COMPLETIONS_COLLECTION_ID=your_completions_collection_id
```

> ⚠️ Never commit your `.env` file. Make sure it's listed in `.gitignore`.

---

## 🙏 Acknowledgements

- Tutorial by [JavaScript Mastery](https://www.youtube.com/@javascriptmastery) on YouTube
- [Appwrite Documentation](https://appwrite.io/docs)
- [Expo Documentation](https://docs.expo.dev/)
- [React Native Documentation](https://reactnative.dev/docs/getting-started)
- [NativeWind Documentation](https://www.nativewind.dev/)
