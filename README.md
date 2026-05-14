# TuneFlow 🎵

> A high-fidelity Music App UI prototype built with Jetpack Compose and Material Design.

<img width="1440" height="900" alt="Screenshot 2026-05-14 at 5 24 48 PM" src="https://github.com/user-attachments/assets/92a82b77-5deb-466e-bb12-b0256c8f8c21" />
<img width="1440" height="900" alt="Screenshot 2026-05-14 at 5 24 57 PM" src="https://github.com/user-attachments/assets/be4a38fc-d598-46ca-ae20-0d92514bfe99" />
<img width="1440" height="900" alt="Screenshot 2026-05-14 at 5 25 00 PM" src="https://github.com/user-attachments/assets/882aeee4-a7e4-4c0e-849a-099d00ee65f9" />
<img width="1440" height="900" alt="Screenshot 2026-05-14 at 5 25 04 PM" src="https://github.com/user-attachments/assets/475c1452-100f-4226-9f1f-ddfcafdbe692" />
<img width="1440" height="900" alt="Screenshot 2026-05-14 at 5 25 41 PM" src="https://github.com/user-attachments/assets/030c2a3b-c110-432e-bda5-1cc8fc48dc18" />
<img width="1440" height="900" alt="Screenshot 2026-05-14 at 5 25 32 PM" src="https://github.com/user-attachments/assets/f4ff5a98-8455-48ab-83a8-5cea23a55fdd" />
<img width="1440" height="900" alt="Screenshot 2026-05-14 at 5 25 21 PM" src="https://github.com/user-attachments/assets/115967f1-f595-47c3-8210-0c005b3093ff" />
<img width="1440" height="900" alt="Screenshot 2026-05-14 at 5 25 16 PM" src="https://github.com/user-attachments/assets/852879c5-3bbf-4bb3-ad5b-8cb22d0fdb65" />


---

## Overview

TuneFlow is an Android UI prototype that demonstrates a modern music streaming application layout built entirely with **Jetpack Compose**. The focus of this project is clean UI architecture, scalable composable design, and Material Design theming — laying a solid foundation for a production-ready music app.

> ⚠️ **Note:** This is a UI-focused project. Audio playback and backend integration are intentionally not included — the goal is to showcase composable structure, layout design, and navigation patterns.

---

## Features

- Modern music app layout with structured screen composition
- Reusable and modular Jetpack Compose components
- Material Design–based theming and typography
- Navigation between screens using Navigation components and menus
- Mock data layer for populating UI during development
- Scalable layout architecture ready for future feature integration

---

## Tech Stack

| Layer | Technology |
|---|---|
| Language | Kotlin |
| UI | Jetpack Compose |
| Design System | Material Design |
| Navigation | Navigation Components |
| Data | UI models and mock data |
| Build System | Gradle (Kotlin DSL) |
| Version Control | Git + GitHub |

---

## Project Structure

```
app/src/main/java/com/rajat/modernmusicappui/
│
├── ui/           # Composable screens and UI components
├── data/         # UI models and mock data
└── MainActivity  # App entry point

res/              # Drawables, themes, and resources
AndroidManifest.xml
build.gradle
```

---

## Getting Started

### Prerequisites
- Android Studio (Arctic Fox or later)
- Android device or emulator running **API 21+**
- JDK 11+

### Setup
```bash
git clone https://github.com/RajatGaidhane1/TuneFlow.git
cd TuneFlow
```

1. Open the project in **Android Studio**
2. Let Gradle sync and download all dependencies
3. Run the app on an emulator or physical device

---

## Screenshots

> _Add screenshots here — suggested: Home screen, Now Playing screen, Navigation menu_

| Home Screen | Now Playing | Menu / Navigation |
|---|---|---|
| `screenshot_home.png` | `screenshot_player.png` | `screenshot_nav.png` |

---

## What This Project Demonstrates

- Structuring a multi-screen Compose UI from scratch
- Building reusable composables for cards, lists, and player controls
- Applying Material Design tokens for consistent theming
- Separating UI components from mock data models
- Laying the groundwork for MVVM integration

---

## Roadmap

Potential next steps to evolve this into a full application:

- [ ] Audio playback with ExoPlayer
- [ ] MVVM architecture with ViewModel and StateFlow
- [ ] Local playlist management with Room
- [ ] REST API integration for track metadata
- [ ] Animated transitions and player gestures
- [ ] Dark mode polish and accessibility improvements

---

## Author

**Rajat Gaidhane**
- GitHub: https://github.com/RajatGaidhane1?tab=repositories
- LinkedIn: https://www.linkedin.com/in/rajat-gaidhane-5383002b7/

---

## License

This project is open source and available under the [MIT License](LICENSE).
