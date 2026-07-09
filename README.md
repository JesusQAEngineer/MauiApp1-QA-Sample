# Game 4 Kids for Android and iOS devices - QA Sample Project 🎮

## Overview
This repository contains a QA Engineer sample project built with **.NET MAUI**.  
The app is a simple **"Catch the Ball" game** implemented in HTML/JavaScript and integrated into MAUI via a WebView.  

The project demonstrates:
- How to structure a MAUI app.
- How to add sample automated tests (placeholders for Appium/MauiUITest).
- How to document and deliver a QA project with a playable APK.

---

## Features
- 🎮 **Game**: A paddle-and-ball game (`Resources/raw/game.html`).
- 📱 **Cross-platform**: Runs on Windows, Android, iOS, and MacCatalyst.
- 🌗 **Theme switching**: Light/Dark mode via AppShell.
- 🧪 **QA tests**: Sample test scripts included in `Tests/`.

---

## QA Testing
The `Tests` folder includes sample test scripts:

- **GamePageTests.cs** → validates GamePage creation and WebView source.
- **ThemeTests.cs** → validates theme switching (Light/Dark).  
- **NavigationTests.cs** → validates Shell routes and navigation.  

⚠️ Note: These tests are **placeholders**.  
They demonstrate structure and intent but must be executed with **Appium** or **MAUI UITest** to interact with the actual UI.

Run tests with:
bash
dotnet test

---

## 🖥️ How to Run Locally

Clone the repository:

bash

git clone https://github.com/JesusQAEngineer/MauiApp1-QA-Sample.git

Open the solution in Visual Studio 2022.

Select target platform (Windows, Android, iOS).

Press F5 to build and run.

---

## 📦 APK Release
A universal APK build is available in the Releases section.

Download it from Releases section.

---

## Installation steps:
📥 Download the universal.apk from the release.

📲 Transfer it to your Android device.

⚙️ Enable Install from unknown sources in device settings.

▶️ Install and run the app.

---

## 🎯 Purpose
This project was created as part of a QA Engineer sample exercise to showcase:

App development with .NET MAUI.

QA test structure and documentation.

Delivery of a working build (APK) with clear instructions.

---

## 👤 Author
Created by Rick (JesusQAEngineer) as a QA Engineer sample project.

