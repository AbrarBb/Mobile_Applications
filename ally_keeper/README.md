# 📱 Ally Keeper

**Ally Keeper** is a powerful Flutter app that helps you keep track of your favorite people, friends, and shared memories. Designed with real human connection in mind, Ally Keeper allows users to organize personal notes, contacts, photos, and social links — and even share real-time locations with mutual users.

---

## 🚀 Features

### 🧠 Memory Keeping & Contact Management
- Save favorite people with names, photos, tags, and descriptions
- Add contact numbers, emails, and social links (Instagram, Facebook, LinkedIn, etc.)
- Write and store personal notes for each saved ally

### 📍 Real-Time Location Sharing
- Share your live location with selected users
- View allies on an interactive map
- Privacy-first: location sharing is mutual and user-controlled

### 📝 Note & Media Storage
- Save text-based notes for events, memories, or important moments
- Attach images from the camera or gallery
- Organize media and notes by tags or relationships

### 🎵 Playlist & Content Sharing *(Upcoming Feature)*
- Share playlists from Spotify/YouTube
- Bookmark favorite songs, links, or media that remind you of people

### 🔒 Privacy & Security
- Secure Firebase Authentication
- Cloud Firestore for fast, real-time database syncing
- Data is private and encrypted; users control what they share

---

## 🧰 Tech Stack

| Layer              | Technology                            |
|--------------------|----------------------------------------|
| Frontend           | Flutter (Dart)                        |
| State Management   | (Optional) Provider / Riverpod        |
| Backend/Cloud      | Firebase Authentication & Firestore   |
| Maps & Location    | `geolocator`, `google_maps_flutter`   |
| Media              | `image_picker`, `photo_view`          |
| Android Native     | Kotlin (Gradle integration)           |
| iOS Native         | Swift (Planned)                       |

---

<h2 id="📁-project-structure">📁 Project Structure</h2>
<p><strong>lib/</strong></p>
<p>├── main.dart               # Entry point</p>
<p>├── models/                # Data models (e.g., Ally, Note)</p>
<p>├── services/              # Firebase &amp; utility services</p>
<p>├── screens/               # UI screens/pages</p>
<p>│   ├── home_screen.dart</p>
<p>│   ├── add_ally_screen.dart</p>
<p>│   └── map_screen.dart</p>
<p>├── widgets/               # Reusable widgets</p>
<p>└── utils/                 # Helpers, constants, etc.</p>
<p><strong>android/</strong></p>
<p>├── app/                   # Android-specific files</p>
<p>│   ├── build.gradle</p>
<p>│   └── google-services.json</p>


## 🛠️ Getting Started

### 🔗 Prerequisites

Make sure the following tools are installed:

- Flutter SDK (latest stable)
- Dart SDK (comes with Flutter)
- Android Studio or VS Code
- Firebase account and project created

### 📦 Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/AbrarBb/Mobile_Applications/tree/main/ally_keeper
   cd ally_keeper
