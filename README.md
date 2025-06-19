# music-player
# Modern Music Player Web Application

A sleek and responsive music player built with HTML, CSS, JavaScript, and React. This application features a modern UI with album art display, playback controls, progress tracking, and a playlist functionality.

## Features

### **Core Functionality**
- Audio playback with play/pause controls
- Track navigation (next/previous song)
- 10-second rewind/fast-forward buttons
- Progress bar with seek functionality
- Time display (current/duration)
- Auto-play next song on track completion

### **UI/UX Design**
- Sleek gradient background with frosted glass player panel
- Responsive layout that works on all screen sizes
- Modern controls with hover effects
- Album art display
- Active track highlighting in playlist
- Smooth animations and transitions

### **Playlist Management**
- Complete song listing with artwork
- Click-to-play functionality
- Visual indicator for current playing track
- Scrollable playlist container

## Built With

- **React** - JavaScript library for building user interfaces
- **HTML5** - Structure of the application
- **CSS3** - Styling and animations
- **JavaScript (ES6+)** - Application logic and functionality

## Setup and Installation

No installation required! This is a client-side application that runs entirely in the browser.

1. Simply open the `music.html` file in any modern web browser
2. Click the play button to start the music player
3. Use the controls to navigate between tracks or adjust playback

## Project Structure

- **music.html** - Main entry file containing all HTML, CSS, and JS code
- The application uses React via CDN links (no build step required)
- All styles are included in a single CSS section within the HTML file
- JavaScript/React code is embedded in the same file using Babel for JSX support

## Customization

To modify the application:

1. **Change Music Library**: Edit the `songs` array in the JavaScript section to include your own tracks:
```javascript
const [songs] = useState([
    {
        id: 1,
        title: "Your Song Title",
        artist: "Artist Name",
        cover: "path/to/image.jpg",
        audio: "path/to/audio.mp3"
    },
    // Add more songs as needed
]);
