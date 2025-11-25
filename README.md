## 📥 Download Large File (250MB)

Due to GitHub’s file size limitations, the main project file has been uploaded to Google Drive.
You can download it from the link below:

👉 **Download File:[Google Drive link](https://drive.google.com/drive/folders/1gI9z0AyMBhP9y_Ks2NH20VRb3Wu45IeM)

## 📄 Project Overview

This repository contains all source code and project resources.
Please download the external file to access the full project package.


## 📝 How to Use

1. Clone or download this repository.
2. Download the large file using the link above.
3. Place the downloaded file inside the project folder (if required by the project structure).
4. open home.html with the browser you will land in home page where you can explore website.


# 🎵 **BEATBAY – Online Music Streaming & Download Platform**

BEATBAY is a fully interactive music streaming platform designed to provide users with a seamless experience for discovering, playing, and managing their favorite songs. The platform features real-time audio playback, dynamic song popups, user-specific download management, and a clean, responsive UI — all powered on the client side using **HTML, CSS, and JavaScript**.

---

## 🚀 **Features**

### 🎧 **Music Playback**

* Popup-based audio player with album art, song title, and full playback controls
* Smooth animations and a responsive design
* Categorized browsing (Trending, New Releases, Popular Artists, Genres)

### 🔐 **User Authentication**

* Client-side registration & login system using LocalStorage
* Session persistence with personalized welcome messages
* Secure logout functionality

### 📥 **Song Download Management**

* Logged-in users can download songs with one click
* Payment confirmation prompt before each download
* Duplicate download detection & prevention
* Each user gets a **unique, personalized download list**
* Ability to delete individual downloaded songs

### 💾 **Client-Side Storage (LocalStorage)**

* Users stored in `users` array
* Logged-in session stored in `logedinuser`
* Downloads stored per user as:

  ```
  downloadedSongs_$<username>
  ```

---

## 🛠️ **Tech Stack**

| Technology           | Purpose                            |
| -------------------- | ---------------------------------- |
| **HTML5**            | Structure & layout                 |
| **CSS3**             | Styling, animations, responsive UI |
| **JavaScript (ES6)** | Application logic, event handling  |
| **LocalStorage**     | Client-side data persistence       |

---

## 📂 **Project Structure**

```
BEATBAY/
│
├── home.html
├── downloads.html
├── login.html
├── style.css
├── audio.js
├── script.js (authentication logic)
├── audio_tracks/ (songs & assets)
└── images/ (thumbnails & icons)
```

---

## 🧩 **How It Works**

### 1. User Flow

* New users register → data saved in LocalStorage
* Returning users log in → session restored
* After login → redirected to **home.html**
* Users can listen to songs and download them

### 2. Download Flow

1. User clicks download
2. Payment confirmation prompt appears
3. If confirmed:

   * Song saved to `downloadedSongs_$<username>`
   * Appears in `downloads.html`

### 3. Delete Flow

* Users can delete any downloaded song
* Removed instantly from:
  * UI
  * LocalStorage

---


## Screenshots
![Screenshot: ](./assets/images/no-filter.JPG)


## ✨ **Key Highlights**

* Clean UI with smooth pop animations
* No backend required — fully client-side
* Modular and reusable JavaScript logic
* LocalStorage-based authentication and state management
* Supports separate download lists for every user

---

## 📌 **Future Enhancements**

You can add this section if you plan to improve:

* Playlist creation
* Server-side authentication (Django / Node.js)
* Backend storage for songs & users
* Dark mode / theme switcher
* Music recommendations based on user behavior

---

## 👨‍💻 **Developer**

**Chethan Gowda A**
Full-Stack Developer | Web Developer | JavaScript Enthusiast

---
