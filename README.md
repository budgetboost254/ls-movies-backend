# 🎬 LS Movies App

**LS Movies** is a streaming app built with Android and Node.js that lets users browse and play movies with subtitles. The app is powered by a lightweight backend and integrates Firebase for authentication.

---

## ✨ Features

- 🔐 Firebase user login (email/password)
- 📦 Cloud-based backend API (`/movies`)
- 🎞️ RecyclerView for browsing content
- 🎥 ExoPlayer with subtitle (VTT) support
- 🔊 Chromecast & Fire TV–friendly design
- ☁️ Ready for Railway or Render deployment

---

## 📱 Android App

### Built With:
- Java & Android SDK
- Firebase Authentication
- Retrofit for API calls
- ExoPlayer for playback
- RecyclerView for movie list

### Setup:
1. Open the project in Android Studio
2. Add your `google-services.json` from Firebase Console
3. Sync Gradle and run

---

## 🔧 Backend API

### Stack:
- Node.js + Express
- CORS enabled
- Static list of movies (replaceable with a DB)
- Subtitle support (VTT format)

### Run Locally:
```bash
cd ls-movies-backend
npm install
node server.js
