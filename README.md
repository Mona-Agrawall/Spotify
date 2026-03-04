# 🎵 Spotify Web Player Clone

A front-end clone of the Spotify Web Player built with HTML and CSS, replicating the core layout and UI of Spotify's desktop web interface.

---

## ✨ Features

- 🎧 **Music Player Bar** — fixed bottom bar with album art, song info, playback controls, and a volume slider
- 📚 **Sidebar** — navigation links (Home, Search) and a Library section with playlist/podcast prompts
- 🏠 **Main Content Area** — scrollable feed with sections: *Recently Played*, *Trending Now Near You*, and *Featured Charts*
- 🃏 **Music Cards** — album/playlist cards with cover art, title, and description
- 📌 **Sticky Top Nav** — stays at the top while scrolling, with Install App and user icon
- 📱 **Responsive Hiding** — certain elements hide on smaller screens (below 1000px)

---

## 📸 Preview

> *(Add a screenshot of the running project here)*

---

## 🛠️ Tech Stack

- **HTML5**
- **CSS3**
- **Font Awesome 6** — icons
- **Google Fonts** — Montserrat typeface

---

## 📁 Project Structure

```
Spotify/
├── index.html          # Main HTML file
├── style.css           # All styling
└── assets/
    ├── logo.png
    ├── library_icon.png
    ├── backward_icon.png
    ├── forward_icon.png
    ├── player_icon1.png – player_icon5.png
    ├── play_musicbar.png
    ├── card1img.jpeg
    └── card2img.jpeg.jpg – card6img.jpeg.jpg
```

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Mona-Agrawall/Spotify.git
cd Spotify
```

### 2. Open in browser

No build tools or dependencies needed — just open `index.html` directly:

```bash
open index.html
```

Or drag and drop the file into your browser.

---

## 📌 Notes

- This is a **static UI clone** — there is no audio playback, login, or backend functionality.
- The music player controls (play, seek, volume) are visual only and not wired to any audio logic.
- Some asset filenames have double extensions (e.g. `card2img.jpeg.jpg`) — this is intentional and matches the `src` paths in the HTML.

---

## 🙋‍♀️ Author

**Mona Agrawal** — [@Mona-Agrawall](https://github.com/Mona-Agrawall)

---

*Built for learning and practice — not affiliated with Spotify.*
