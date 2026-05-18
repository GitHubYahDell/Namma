# 🛕 Virasat-Namma Guide  
### *Every Stone Has a Story.*

> A culturally immersive Android app that transforms smartphones into digital heritage companions for exploring Karnataka’s forgotten temples, ruins, inscriptions, and hidden historical treasures.

---

## 🌏 About The Project

**Virasat-Namma Guide** is a Kotlin-based Android application built to preserve and promote Karnataka’s rich cultural heritage through technology.  

Instead of just showing locations on a map, the app recreates the feeling of walking with a local historian — combining:

- 📍 Smart heritage discovery  
- 🗣️ Bilingual storytelling (English + Kannada)  
- 🔍 QR-powered hidden facts  
- 🎧 Audio history guides  
- 🏛️ Temple-inspired visual design  
- 📖 A personal digital travel passport  

The project focuses on **offline-first tourism experiences** and aims to digitally preserve lesser-known heritage sites that are slowly disappearing from public memory.

---

# ✨ Experience Highlights

### 🧭 Discover Hidden Heritage
Explore simulated nearby heritage sites across Karnataka using seeded local data.

### 🌐 Dual-Language Support
Switch instantly between **English** and **Kannada** without restarting the app.

### 🔎 QR Code Unlock System
Scan heritage QR codes using **Google ML Kit + CameraX** to reveal exclusive hidden facts.

### 🎵 Interactive Audio Narration
Listen to short historical audio guides with smooth playback controls.

### 🛕 Digital Travel Passport
Check in at heritage sites and build your own cultural journey timeline.

### 🎨 Temple-Inspired UI
Designed with:
- Terracotta tones
- Stone-textured palettes
- Hoysala-inspired aesthetics
- Kannada typography accents

---

# 🧱 Tech Stack

| Technology | Purpose |
|---|---|
| **Kotlin** | Android Development |
| **Room DB** | Offline persistence |
| **Google ML Kit** | QR/Barcode scanning |
| **CameraX** | Camera integration |
| **MediaPlayer** | Audio guide playback |
| **Material 3** | Modern UI components |
| **MVVM Architecture** | Clean architecture pattern |

---

# 📸 Demo QR Site IDs

Generate QR codes using these exact values:

```text
SITE-BELUR-001
SITE-HAMPI-002
SITE-AIH-003
```

🧪 Emulator testing is also supported using the built-in:

```text
Mock Scan: SITE-BELUR-001
```

button inside the QR Scanner screen.

---

# 🚀 Running The Project

## 1️⃣ Clone The Repository

```bash
git clone <your-repository-url>
```

---

## 2️⃣ Open In Android Studio

```text
File → Open → Select Project Folder
```

Allow Android Studio to complete:
- Gradle Sync
- Dependency installation
- SDK setup

---

## 3️⃣ Install Required SDK

Install:

```text
Android 15 (API 35)
```

via:

```text
Tools → SDK Manager
```

---

## 4️⃣ Create Emulator

Recommended:

```text
Pixel 6 / Pixel 7
API 35 Image
```

---

## 5️⃣ Run The App

Click:

```text
▶ Run
```

---

# 🧪 Suggested Test Flow

### 🏠 Home Screen
Browse nearby heritage locations.

### 🏛️ Site Detail Screen
- Read site history
- Toggle Kannada/English
- View architecture details

### 🎧 Audio Guide
Test:
- Play
- Pause
- Resume

### 📍 Check-In
Tap **Check In** to save the visit locally.

### 🛂 Travel Passport
Verify check-ins persist after app restart.

### 📷 QR Scanner
Test:
- Real QR codes
- Mock scan button

---

# 📂 Core Project Structure

```text
app/
 ├── java/com/example/virasatnammaguide/
 │    ├── MainActivity.kt
 │    ├── SiteDetailActivity.kt
 │    ├── QrScannerActivity.kt
 │    ├── HeritageRepository.kt
 │    ├── AppDatabase.kt
 │
 ├── res/layout/
 │    ├── activity_main.xml
 │    ├── activity_site_detail.xml
 │    ├── activity_qr_scanner.xml
```

---

# 🛡️ Offline-First Philosophy

This application is intentionally designed to work **without requiring internet access after installation**.

Why?

Because many real heritage locations:
- exist in rural areas
- have poor connectivity
- lack digital infrastructure

---

# 🎯 Vision

Virasat-Namma is more than a tourism app.

It is a small step toward:
- preserving oral history
- reviving forgotten monuments
- promoting local tourism
- creating cultural pride through technology

---

# 🏆 Future Scope

- 🌙 Dark Mode
- ⭐ Favourite Sites
- 🧠 AI-generated Heritage Quiz
- 📍 Smart Geofence Notifications
- 🗺️ Live Maps Integration
- ☁️ Cloud Sync
- 📤 Social Sharing Cards

---

# 🤝 Contributors

Built with passion for:
- Karnataka heritage 🛕
- Smart tourism 🌍
- Cultural storytelling 📖
- Android development 📱

---

# 📜 License

This project is intended for educational and academic purposes.  
Feel free to modify and expand it for learning or showcase projects.

---

<div align="center">

### 🏛️ Virasat-Namma  
#### *"Turning Every Smartphone Into A Digital Historian."*

</div>
