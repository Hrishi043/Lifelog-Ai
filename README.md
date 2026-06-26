# LifeLog AI 📔✨
> **Your Privacy-First Intelligent Diary & Memory Assistant**

**LifeLog AI** is a personal journal and timeline app that lets you log your daily moments using text, photos, and voice recordings. By combining a local-first offline database with secure generative AI, the app weaves your day's events into reflective journal entries and lets you ask questions directly to your memory.

---

## 🚀 Key Features

*   **Multimodal Log Intake**: Save quick thoughts, track locations, snap photos, or record voice memos with live visualizer feed.
*   **AI Daily Summaries**: Consolidates chronological moments into a cohesive, first-person narrative entry.
*   **Highlight of the Day**: AI detects the most meaningful event of your day and compiles it into a headline.
*   **Natural Language Memory Search**: Chat with your past! Ask questions like *"Where did I go last Sunday?"* or *"What was the key topic in my voice note yesterday?"* to search your history.
*   **Insights & Analytics**: Review visual breakdown graphs, weekly logging activity levels, and moment statistics.
*   **Privacy First**: All database logs, photos, and audio files are stored locally on your device.

---

## 📥 Installation & Downloads

### 📱 Android (Direct Download)
[![Download APK](https://img.shields.io/badge/Download-APK-green?style=for-the-badge&logo=android)](https://github.com/Hrishi043/Lifelog-Ai/raw/main/lifelog_ai_release.apk)

1. Click the button above to download **`lifelog_ai_release.apk`** directly.
2. Open the file on your Android device.
3. If prompted, enable *"Install from Unknown Sources"* in your security settings.
4. Launch the app and start logging!

### 💻 Windows Desktop
1.  Download the **`lifelog_ai_windows.zip`** file from the latest release (or build from source).
2.  Extract the ZIP folder to a local directory (e.g., `C:\Program Files\LifeLog AI`).
3.  Double-click **`lifelog_ai.exe`** to run the app.
4.  *(Optional)* Right-click `lifelog_ai.exe` and select *"Pin to Start"* or *"Create Desktop Shortcut"* for quick access.

---

## ⚙️ AI Engine Configuration

LifeLog AI values your privacy and uses a **Bring-Your-Own-Key (BYOK)** model. By default, the app runs locally offline using a rules engine. To unlock intelligent summaries and memories search, add your own API credentials:

1.  Open the app and navigate to **Settings ⚙️**.
2.  Under **AI Intelligence Engine**, choose either **Google Gemini AI** or **OpenAI GPT**.
3.  Paste your API key:
    *   **Gemini Key**: Get a free or pay-as-you-go key from [Google AI Studio](https://aistudio.google.com/).
    *   **OpenAI Key**: Get a key from the [OpenAI Platform](https://platform.openai.com/).
4.  Choose your model (e.g., `gemini-1.5-flash` or `gpt-4o-mini` are recommended for fast, cost-effective processing).
5.  All API keys are saved **strictly locally** inside your app documents directory and are never shared or sent to external logging servers.

---

## 💾 Backups & Data Management

*   **Database Backups**: You can export your SQLite log database (`lifelog_ai.db`) at any time from Settings.
*   **Restore Utility**: Load a previously exported backup file to restore your diary history when switching devices.
*   **Data Wipe**: Use the **Clear All Logs** option to permanently erase all local databases, voice notes, photos, and cached AI reports from your device storage.

---

## 🛠️ Tech Stack & Architecture (Overview)
*   **Frontend**: Flutter / Dart
*   **State Management**: Riverpod
*   **Database**: SQLite (`sqflite`)
*   **Integrations**: Google Generative AI Dart client, OpenAI REST API, `flutter_local_notifications`.

---

## 🛡️ License & Privacy Assurance

LifeLog AI is built to keep your personal thoughts secure. Since the source code is kept in a private repository to prevent redistribution leaks, this public repository is used strictly to host release binaries (`.apk`, `.exe`), guide installers, and publish version updates.
