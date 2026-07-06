```markdown
# 🧸 Kids Health — Pediatric Constipation Care

<p align="center">
  <!-- Replace with your actual app icon path once uploaded -->
  <img src="app/src/main/ic_launcher-playstore.png" width="120" alt="Kids Health logo"/>
</p>

<p align="center">
  <a href="https://cafebazaar.ir/app/com.example.constipationproject?l=en"><img src="https://img.shields.io/badge/CafeBazaar-Download-71C414?logo=android&logoColor=white" alt="Download on CafeBazaar"/></a>
  <img src="https://img.shields.io/badge/Platform-Android-3DDC84?logo=android&logoColor=white" alt="Android"/>
  <img src="https://img.shields.io/badge/License-MIT-yellow" alt="License"/>
  <img src="https://img.shields.io/badge/Focus-Pediatric%20Gastroenterology-0088CC" alt="Pediatric Gastroenterology"/>
  <img src="https://img.shields.io/badge/Status-Published-success" alt="Published"/>
</p>

> **Kids Health** is an Android companion application designed to promote self-care culture for children suffering from constipation and to increase awareness among their parents. Developed in collaboration with medical professors, it acts as a trusted friend and guide for families.

---

## ⚠️ Medical Disclaimer

Kids Health is an **educational and self-care support tool**. It is **not** a medical device and should not replace professional medical advice, diagnosis, or treatment. Always consult a qualified pediatrician or pediatric gastroenterologist for your child's medical condition.

---

## 🌟 Introduction & Philosophy

We believe that the future belongs to the pure hearts of the children of our land.

**Kids Health is not your doctor; it is your friend.** A trusted friend that tells you what steps to take to care for your child. 

Our mission is to leverage information technology and modern communication sciences to play a part—however small—in promoting a self-care culture for children with constipation and increasing parental awareness.

This project was professionally and knowledge-driven, designed and developed utilizing the expertise of esteemed professors from **Urmia University of Medical Sciences** in the fields of:
- Health Information Management
- Medical Informatics
- Pediatric Gastroenterology

---

## ✨ Features

| Module | Description |
|---|---|
| 📚 **Educational Content** | Evidence-based guidelines and tips for managing pediatric constipation at home. |
| 🍎 **Dietary Guides** | Recommendations on fiber, fluids, and nutrition tailored for children's digestive health. |
| 📝 **Self-Care Tracking** | Tools to help parents track their child's bowel habits and identify patterns. |
| 👨‍👩‍👧 **Parental Awareness** | Clear, accessible information to help parents understand triggers and preventive measures. |
| 🔒 **Privacy-First** | All data remains securely on the user's device. |

---

## 📸 Screenshots

<p align="center">
  <!-- Replace placeholders with your actual screenshots -->
  <img src="screenshots/home.png" width="200" alt="Home Screen"/>
  <img src="screenshots/education.png" width="200" alt="Educational Content"/>
  <img src="screenshots/tracker.png" width="200" alt="Habit Tracker"/>
  <img src="screenshots/settings.png" width="200" alt="Settings"/>
</p>

---

## 📚 References & Medical Sources

The content and guidelines within this application are rigorously backed by peer-reviewed medical literature and standard pediatric textbooks, including:

1. **Nelson Textbook of Pediatrics** (2023 Edition)
2. Related research articles published in reputable scientific journals indexed in:
   - Scopus
   - PubMed
   - Web of Science

---

## 🚀 Getting Started

### Prerequisites
- Android Studio (Giraffe or newer recommended)
- JDK 11 or higher
- Android device or emulator running API 21+ (Lollipop or higher)

### Build & Run

```bash
# 1. Clone the repository
git clone https://github.com/sinaveisi/KidsHealth-Constipation.git
cd KidsHealth-Constipation

# 2. Build the debug APK
./gradlew assembleDebug

# 3. Install on a connected device
./gradlew installDebug
```

### Download the Released APK
The app is currently published on the Iranian Android market:

👉 **[Download Kids Health from CafeBazaar](https://cafebazaar.ir/app/com.example.constipationproject?l=en)**

---

## 🛠️ Tech Stack

| Category | Technology |
|---|---|
| **Platform** | Android (Native) |
| **Language** | Kotlin |
| **UI Toolkit** | Jetpack Compose |
| **Architecture** | MVVM + Repository Pattern |
| **Database** | Room |
| **Dependency Injection** | Hilt / Dagger |

---

## 📁 Project Structure

```
app/src/main/java/com/example/constipationproject/
├── data/                # Data models, local database, and repository
│   ├── models/
│   ├── repository/
│   └── local/
├── di/                  # Dependency Injection modules
├── ui/                  # UI components (Activities/Fragments/Composables)
│   ├── screens/         # Home, Education, Tracker, Settings
│   ├── adapter/         # RecyclerView adapters (if applicable)
│   └── theme/           # Colors, Typography, Shapes
└── util/                # Utility classes and extensions
```

---

## 🤝 Contributing

Contributions are welcome! If you have suggestions for improving the medical content, UI/UX, or codebase:

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/your-feature`
3. Commit using Conventional Commits (`feat:`, `fix:`, `docs:`…)
4. Open a Pull Request

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

Special thanks to the faculty and pediatric gastroenterology specialists at **Urmia University of Medical Sciences** for their clinical oversight, and to the parents and children who inspired this project.

---

## 📫 Contact

**Sina Veisi**
- App on CafeBazaar: [Kids Health](https://cafebazaar.ir/app/com.example.constipationproject?l=en)
```
