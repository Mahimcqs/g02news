# g02news
newsapp
> Edited for use in IDX on 07/09/12

# Welcome to your Expo app 👋

This is an [Expo](https://expo.dev) project created with [`create-expo-app`](https://www.npmjs.com/package/create-expo-app).

## Get started

#### Android

Android previews are defined as a `workspace.onStart` hook and started as a vscode task when the workspace is opened/started.

Note, if you can't find the task, either:
- Rebuild the environment (using command palette: `IDX: Rebuild Environment`), or
- Run `npm run android -- --tunnel` command manually run android and see the output in your terminal. The device should pick up this new command and switch to start displaying the output from it.

In the output of this command/task, you'll find options to open the app in a

- [development build](https://docs.expo.dev/develop/development-builds/introduction/)
- [Android emulator](https://docs.expo.dev/workflow/android-studio-emulator/)
- [Expo Go](https://expo.dev/go), a limited sandbox for trying out app development with Expo

You'll also find options to open the app's developer menu, reload the app, and more.

#### Web

Web previews will be started and managred automatically. Use the toolbar to manually refresh.

You can start developing by editing the files inside the **app** directory. This project uses [file-based routing](https://docs.expo.dev/router/introduction).

## Get a fresh project

When you're ready, run:

```bash
npm run reset-project
```

This command will move the starter code to the **app-example** directory and create a blank **app** directory where you can start developing.

## Learn more

To learn more about developing your project with Expo, look at the following resources:

- [Expo documentation](https://docs.expo.dev/): Learn fundamentals, or go into advanced topics with our [guides](https://docs.expo.dev/guides).
- [Learn Expo tutorial](https://docs.expo.dev/tutorial/introduction/): Follow a step-by-step tutorial where you'll create a project that runs on Android, iOS, and the web.

## Join the community

Join our community of developers creating universal apps.

- [Expo on GitHub](https://github.com/expo/expo): View our open source platform and contribute.
- [Discord community](https://chat.expo.dev): Chat with Expo users and ask questions.
# 📰 Way2News-Style Flutter App

A modern, Firebase-powered mobile news application built with Flutter. Inspired by Way2News, this app offers real-time regional news in multiple languages (English & Telugu), text-to-speech support, and a smooth user interface.

---

## 🚀 Features

- 🔥 Real-time news from Firebase Firestore
- 📂 News categories: Top News, Politics, Cinema, Sports, Tech
- 🎙️ Text-to-Speech support for headlines
- 🌐 English & Telugu language toggle
- 🧑‍💻 Admin upload panel to add news (title, content, image, language)
- 📲 Push Notifications with Firebase Cloud Messaging (FCM)
- 🧭 Bottom navigation for easy access
- ⚡ Fast and responsive UI

---

## 🧱 Tech Stack

- **Flutter** (Frontend)
- **Firebase** (Firestore, Auth, FCM)
- **flutter_tts** for voice
- **flutter_localizations** for i18n

---

## 🛠️ Getting Started

### Prerequisites
- Flutter SDK
- Android Studio or VS Code
- Firebase Project

### Setup Instructions

1. **Clone this repository**:
   ```bash
   git clone https://github.com/yourusername/way2news-clone.git
   cd way2news-clone
