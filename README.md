# ⚡ SAM AI - Intelligent Mobile IDE & Assistant

An intelligent, next-generation mobile development environment and AI coding assistant designed to empower developers to create, edit, debug, and run projects seamlessly on the go.

---

## 🌟 Key Features

- 🧠 **AI-Powered Code Generation & Assistance**: Intelligent coding partner capable of generating boilerplate, debugging errors, and suggesting optimizations in real time.
- 💻 **Mobile IDE Experience**: Built-in editor with syntax highlighting, project file tree navigation, and live preview capabilities.
- 🎙️ **Voice-Driven Assistant**: Interactive voice commands and conversational agent mode for hands-free coding assistance.
- 📁 **Project Management**: Create, manage, and organize multiple codebases effortlessly.
- 🎨 **Modern & Sleek UI**: Fully reactive Jetpack Compose interface with dark theme aesthetics and smooth animations.

---

## 🚀 Getting Started

### Prerequisites
- [Android Studio Ladybug / Koala or newer](https://developer.android.com/studio)
- Android SDK (API 34+)
- JDK 17+

### Installation & Local Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/theshlok18/ide-sam-Ai.git
   cd ide-sam-Ai
   ```

2. **Open in Android Studio:**
   - Launch Android Studio.
   - Select **Open** and choose the `ide-sam-Ai` directory.
   - Allow Gradle to sync dependencies.

3. **Configure Environment Variables:**
   - Copy `.env.example` to `.env`:
     ```bash
     cp .env.example .env
     ```
   - Add your API credentials in `.env`:
     ```env
     GEMINI_API_KEY=your_api_key_here
     ```

4. **Build & Run:**
   - Connect an Android device with USB debugging enabled or launch an Android Emulator.
   - Click **Run** (`Shift + F10`) in Android Studio.

---

## 🛠️ Architecture & Tech Stack

- **UI Framework:** Kotlin & Jetpack Compose
- **Architecture:** MVVM + Clean Architecture Patterns
- **Database / Local Storage:** Room DB
- **Networking & AI Integration:** Google AI Gemini SDK / REST API Client
- **Theme:** Custom Material 3 Dark/Light Palette

---

## 👨‍💻 Author & Credits

- **Creator & Developer:** [Shlok Sathe](https://github.com/theshlok18) (@theshlok18)
- **Repository:** [ide-sam-Ai](https://github.com/theshlok18/ide-sam-Ai)

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
