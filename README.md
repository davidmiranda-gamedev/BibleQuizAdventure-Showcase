# 📖 Bible Quiz Adventure

![Unity](https://img.shields.io/badge/Engine-Unity-black?logo=unity)
![C#](https://img.shields.io/badge/Language-C%23-purple)
![Platform](https://img.shields.io/badge/Platform-Android%20%7C%20Windows-green)

## Status

✅ Version 1.0 Released

📱 Android

🌐 WebGL

🎮 Portfolio Project

🛠 Actively Maintained

> An interactive Christian educational game that transforms Bible learning into an engaging adventure through level progression, exploration, and challenge-based gameplay.

---

🔗 Quick Links

🎮 [Play in Browser](https://davidmiranda.itch.io/bible-quiz-adventure)

📱 [Android APK](https://drive.google.com/drive/folders/1cCemW7HTBfC2xpgbDTrmvBrgd2DKxlo3?usp=sharing)

🎥 [Gameplay Demo](https://drive.google.com/file/d/1gGnLD8D_DEmiRa6ylt42AY00QmhGN1Ua/view?usp=sharing)

---

## Overview

Bible Quiz Adventure is a cross-platform Christian educational quiz game developed using Unity 6 and C#. It combines story-driven progression, interactive gameplay, and educational content to make learning Scripture engaging for players of all ages.

Rather than functioning as a traditional quiz application, the game incorporates modern game design principles—including level progression, persistent save systems, star-based achievements, and timed challenges—to create a rewarding learning experience.

The project was designed with a modular manager-based architecture, reusable UI systems, and data-driven content using ScriptableObjects, allowing future Bible stories and levels to be added with minimal code changes.

---

---

# ✨ Features

Bible Quiz Adventure combines educational gameplay with scalable Unity systems to deliver an engaging Bible learning experience.

## 🎮 Gameplay Features

* 📖 **Adventure Mode** — Progress through 20 handcrafted Bible story levels inspired by the Book of Genesis.
* ⏱️ **Time Challenge Mode** — Answer as many questions as possible within 60 seconds while competing against your personal best score.
* ⭐ **Star Rating System** — Earn up to three stars on each level based on your performance.
* 🔓 **Level Progression** — Unlock new levels as you complete previous challenges.
* 💾 **Persistent Save System** — Player progression, unlocked levels, earned stars, and high scores are automatically saved.
* 🎲 **Randomized Quiz Experience** — Time Challenge randomizes both questions and answer choices for high replayability.
* 📚 **Bible-Based Learning** — Questions are based on the English Standard Version (ESV) and designed to reinforce biblical knowledge.

---

## 🛠 Technical Features

* 🏗 **Manager-Based Architecture** for modular and maintainable gameplay systems.
* 📦 **ScriptableObject-Driven Quiz Database** for reusable and scalable level content.
* 🎨 **Reusable UI Framework** with shared interfaces across multiple game modes.
* 🔄 **Scene Transition System** with smooth fade animations between scenes.
* 🔊 **Centralized Audio Management** supporting music, sound effects, and persistent settings.
* 💾 **PlayerPrefs Persistence** for saving progression, stars, settings, and high scores.
* 📱 **Mobile-First UI Design** optimized for portrait orientation on Android devices.
* 🌐 **Cross-Platform Deployment** supporting both Android and WebGL builds.


---

🏗 Architecture

Bible Quiz Adventure was designed using a modular, manager-based architecture to promote scalability, maintainability, and code reusability. Gameplay systems are separated into dedicated managers with clear responsibilities, making the project easier to extend as additional Bible stories, game modes, and features are introduced.

Instead of creating separate scenes for every level, the game uses a single reusable Quiz Scene that dynamically loads quiz content from ScriptableObjects. This data-driven approach minimizes duplicated code and allows new levels to be created without modifying gameplay logic.

Architecture Highlights
🧩 Modular manager-based design
📦 ScriptableObject-driven quiz content
🔄 Reusable Quiz Scene for every Adventure level
💾 Persistent player progression using PlayerPrefs
🎨 Reusable UI components shared across game modes
🎵 Centralized audio management
🌐 Cross-platform deployment for Android and WebGL
Core Systems
System	Responsibility
AdventureManager	Handles level selection, navigation, and game flow within Adventure Mode.
QuizManager	Controls quiz gameplay, question loading, answer validation, scoring, and progression.
ProgressionManager	Saves and loads unlocked levels, earned stars, and player progression.
AudioManager	Manages background music, sound effects, and user audio settings across all scenes.
SceneTransitionManager	Provides reusable fade transitions between scenes for a polished user experience.
UIManager	Coordinates shared UI elements, menus, and interface interactions.
PanelAnimator	Handles panel animations for smoother UI transitions.
ConfirmationPanelManager	Displays reusable confirmation dialogs throughout the application.
Design Principles

During development, the project followed several software engineering principles:

Separation of responsibilities between gameplay systems
Data-driven content using ScriptableObjects
Reusable UI components to reduce duplication
Centralized managers for shared functionality
Configurable gameplay values through the Unity Inspector
Scalable architecture prepared for future Bible story expansions

This structure allows additional Bible books, quiz levels, and gameplay features to be integrated with minimal changes to the existing codebase.
---

## Core Gameplay

### Adventure Mode

Progress through a structured journey of Bible-themed levels featuring carefully curated questions based on biblical stories, characters, teachings, and events.

Players must complete stages, earn stars, and unlock new levels as they continue their adventure through Scripture.

### Endless Mode

Challenge yourself against the clock and answer as many Bible questions as possible before time runs out.

Designed for replayability, Endless Mode encourages players to improve their knowledge while competing against their personal best scores.

### Learn Through Play

Questions are designed to reinforce biblical understanding while maintaining an engaging gameplay loop that encourages continued learning and progression.

---

## Key Features

### Level-Based Progression

Unlock new stages as you complete Bible-themed challenges and advance through the adventure.

### Structured Bible Learning

Questions are organized around important biblical stories, teachings, and historical events.

### Endless Challenge Mode

Fast-paced gameplay that rewards quick thinking and biblical knowledge.

### Star Reward System

Track your performance and progress through a rewarding achievement system.

### Mobile-Friendly Interface

Designed specifically for Android devices with intuitive portrait-oriented gameplay.

### Educational Game Design

Combines gamification principles with biblical education to create meaningful learning experiences.

---

## Screenshots

<table>
<tr>
<td align="center">
<b>Quiz Gameplay</b><br>
<img src="screenshots/quiz-mode.png" width="250">
</td>

<td align="center">
<b>Main Menu</b><br>
<img src="screenshots/main-menu.png" width="250">
</td>

<td align="center">
<b>Adventure Map</b><br>
<img src="screenshots/adventure-levels.png" width="250">
</td>
</tr>
</table>


---

## Project Highlights

- Developed as a complete Bible-learning game experience
- Features both Adventure Mode and Endless Mode
- Designed for Android and Windows platforms
- Implements scalable level progression architecture
- Encourages biblical learning through interactive gameplay
- Combines education, gamification, and user engagement principles
- Built as a standalone educational game product

---

## Gameplay Demo

Watch a short gameplay demonstration showcasing Adventure Mode, level progression, and Endless Mode gameplay.

🎥 Bible Quiz Adventure Gameplay Demo

[Watch Gameplay Demo](YOUR_VIDEO_LINK)

---

## Technologies Used

- Unity Engine
- C#
- TextMeshPro
- Unity UI System
- PlayerPrefs Save System
- Mobile Game Development
- Android Build Pipeline
- Windows Build Pipeline
- Git & GitHub

---

## My Contributions

As the sole developer of Bible Quiz Adventure, I was responsible for:

- Game Design
- UI/UX Design
- Gameplay Programming
- Quiz System Development
- Level Progression System
- Endless Mode Development
- Save System Implementation
- Android and Windows Deployment
- Testing and Optimization

---

## Future Improvements

- Additional Bible Stories and Events
- Expanded Question Database
- Achievement System
- Daily Challenges
- Online Leaderboards
- Cloud Save Support
- Additional Educational Game Modes

---

## Technical Challenges

During development, several gameplay systems were designed and implemented:

- Dynamic question management system
- Adventure mode progression architecture
- Endless mode timer framework
- Persistent player progression
- Star-based completion system
- Mobile-responsive UI implementation
- Data-driven quiz structure
- Cross-platform deployment pipeline

---

## Developer

**David Nathaniel Miranda**

Software Developer | Unity Game Developer | Web Developer

GitHub:  
[David Miranda GitHub](https://github.com/davidmiranda-gamedev)

LinkedIn:  
[David Miranda LinkedIn](https://www.linkedin.com/in/davidnmiranda/)

---

⭐ If you enjoyed this project, feel free to explore my other repositories and educational game projects.
