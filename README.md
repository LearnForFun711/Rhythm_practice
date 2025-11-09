# Rhythm Practice Generator
## 節奏練習生成器

A web-based rhythm practice tool for music students, featuring two practice modes and adjustable tempo, all contained in a single HTML file.

### Features
- **Two Skill Levels**:
  - **Grade 3 (Advanced)**: Half Note, Dotted Quarter Note, Eighth Note, Quarter Note.
  - **Grade 6 (Beginner)**: Complex sixteenth-note patterns including Two Eighth Notes, Dotted Eighth & Sixteenth, Eighth & Two Sixteenths, and Four Sixteenth Notes.
- **Two Practice Modes**:
  - **Custom Mode**: Drag and drop rhythm blocks to build and play your own two-measure patterns.
  - **Random Generate Mode**: Listen to a randomly generated rhythm twice, clap along, and then reveal the notation to check your accuracy.
- **Adjustable Tempo**: Use the BPM slider to practice at different speeds (from 40 to 200 BPM).
- **Audio Playback**: Hear the rhythms you create or the ones generated for you.
- **All-in-One File**: The entire application is contained within a single `index.html` file for maximum portability and ease of use.

### How to Use
1.  Open `index.html` in a modern web browser with an internet connection.
2.  Select a grade level (Grade 3 or Grade 6).
3.  Adjust the BPM slider to your desired tempo.
4.  Choose a mode:
    - **Custom Mode**: Drag rhythm images into the measure boxes. Click "Play" to listen or "Clear" to start over.
    - **Random Generate Mode**: Click "Generate New Rhythm", then "Play" to listen. After practicing, click "Show Rhythm" to see the notation.

### Hosting on GitHub Pages
1.  Create a new repository on GitHub.
2.  Upload the `index.html` file and the entire `MusicNotePhoto` folder to the repository.
3.  In the repository settings, go to the "Pages" section.
4.  Choose the `main` branch as the source and click "Save".
5.  Your site will be available at `https://[your-username].github.io/[your-repository-name]/`.

### Technologies Used
- HTML5
- CSS3
- JavaScript
- VexFlow (Music Notation Library)
