# 🎵 Mood Music App  

A Flutter-based music recommendation application that curates songs based on the user's **current mood**.  
With a clean UI and lightweight logic, it delivers instant recommendations from a curated library of **100+ songs** stored in a local JSON dataset.  

---

## ✨ Features  

- **Mood-based Recommendations**  
  - Choose from moods like *Happy*, *Sad*, *Calm*, etc.  
  - Each mood triggers a **random selection** from the pre-tagged song pool.  

- **Local JSON Data Handling**  
  - 100+ songs with mood metadata stored in a structured JSON file.  
  - Eliminates the need for API calls — **fast and offline-friendly**.  

- **Flutter-Optimized Performance**  
  - Built with Flutter’s widget tree efficiency for smooth navigation.  
  - Lightweight state management for rapid mood-to-song response.  

- **Clean & Minimal UI**  
  - Intuitive mood selection interface.  
  - Dynamic display of selected song with its metadata.  

---

## 🛠️ Technical Overview  

### Architecture  
- **Framework:** Flutter (Dart)  
- **State Management:** Minimal `setState` for simplicity (can be scaled to `Provider` or `Riverpod`).  
- **Data Source:** Local JSON asset containing:  
  ```json
  [
    {
      "title": "Song Title",
      "artist": "Artist Name",
      "mood": "happy",
      "url": "https://example.com/song.mp3"
    }
  ]
