# 📖 Bible Quiz Adventure

![Unity](https://img.shields.io/badge/Engine-Unity-black?logo=unity)
![C#](https://img.shields.io/badge/Language-C%23-purple)
![Platform](https://img.shields.io/badge/Platform-Android%20%7C%20WebGL-green)

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

## 📚 Overview

Bible Quiz Adventure is a cross-platform Christian educational quiz game developed using Unity 6 and C#. It combines story-driven progression, interactive gameplay, and educational content to make learning Scripture engaging for players of all ages.

Rather than functioning as a traditional quiz application, the game incorporates modern game design principles—including level progression, persistent save systems, star-based achievements, and timed challenges—to create a rewarding learning experience.

The project was designed with a modular manager-based architecture, reusable UI systems, and data-driven content using ScriptableObjects, allowing future Bible stories and levels to be added with minimal code changes.

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

## 🏗 Architecture

Bible Quiz Adventure was designed using a modular, manager-based architecture to promote scalability, maintainability, and code reusability. Gameplay systems are separated into dedicated managers with clear responsibilities, making the project easier to extend as additional Bible stories, game modes, and features are introduced.

Instead of creating separate scenes for every level, the game uses a single reusable Quiz Scene that dynamically loads quiz content from ScriptableObjects. This data-driven approach minimizes duplicated code and allows new levels to be created without modifying gameplay logic.

### Core Systems

| System | Responsibility |
|---------|----------------|
| **AdventureManager** | Handles level selection and Adventure Mode flow. |
| **QuizManager** | Controls quiz gameplay, scoring, answer validation, and progression. |
| **ProgressionManager** | Saves unlocked levels, stars, and player progress. |
| **AudioManager** | Manages music, sound effects, and audio settings. |
| **SceneTransitionManager** | Handles reusable scene fade transitions. |
| **UIManager** | Coordinates shared UI interactions. |
| **PanelAnimator** | Plays UI panel animations. |
| **ConfirmationPanelManager** | Displays reusable confirmation dialogs. |

### Design Principles

- Modular manager-based architecture
- Separation of responsibilities
- ScriptableObject-driven content
- Reusable UI systems
- Configurable gameplay values through the Unity Inspector
- Scalable architecture for future Bible story expansions

---

## 📸 Screenshots

Explore key moments from Bible Quiz Adventure, showcasing the user interface, adventure progression, and quiz gameplay.

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

## 🛠 Technologies Used

| Technology          | Purpose               |
| ------------------- | --------------------- |
| **Unity 6**         | Game Engine           |
| **C#**              | Gameplay Programming  |
| **TextMeshPro**     | User Interface Text   |
| **Unity UI System** | User Interface        |
| **PlayerPrefs**     | Save Data Persistence |
| **Git & GitHub**    | Version Control       |
| **Android**         | Mobile Deployment     |
| **WebGL**           | Browser Deployment    |

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
- Time Challenge Development
- Android and WebGL Deployment

---

## 🗺️ Roadmap

### Version 1.1

- 🔥 Time Challenge streak bonus
- ⭐ Total star counter
- 💬 Bible Guide / Chat feature
- 📖 Exodus storyline

### Future Releases

- Additional Bible books
- Expanded question database
- Achievement system
- Daily challenges
- Cloud save support

---

## 📖 What I Learned

Developing Bible Quiz Adventure strengthened my experience in:

- Unity 6 game development
- C# application architecture
- Data-driven development using ScriptableObjects
- Persistent save and progression systems
- Mobile-first UI/UX design
- Cross-platform deployment for Android and WebGL
- Version control using Git and GitHub

This project reinforced the importance of writing modular, maintainable, and scalable code while delivering a polished user experience.

---

## 👨‍💻 Developer

**David Nathaniel Miranda**

Software Developer | Unity Game Developer | Web Developer

GitHub:  
[David Miranda GitHub](https://github.com/davidmiranda-gamedev)

LinkedIn:  
[David Miranda LinkedIn](https://www.linkedin.com/in/davidnmiranda/)

---

⭐ If you enjoyed this project, feel free to explore my other repositories and educational game projects.
