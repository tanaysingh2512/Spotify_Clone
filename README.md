# Spotify Clone (HTML, CSS, JavaScript)

A front-end Spotify-inspired music player built using HTML, CSS, and JavaScript.  
This project features a modern UI, a functioning audio player, a dynamic song list, and interactive controls such as play/pause, next/previous, and a seekable progress bar.

## Features

- Clean Spotify-style user interface
- Play, pause, next, and previous song functionality
- Dynamic song list with individual play buttons
- Seekable progress bar that syncs with audio
- Real-time progress and audio position updates
- Responsive layout structure
- Easily extendable with more songs, features, or backend integration

## Tech Stack

- HTML
- CSS
- JavaScript (Vanilla JS)


## How It Works

- The script loads an array of song objects containing:
  - Song name
  - File path
  - Cover image path
- Clicking on a song updates the audio source and UI state.
- The master play button controls the main audio player.
- The progress bar listens to time updates and allows manual seeking.
- Next and previous buttons navigate through the song list.

## How to Run

1. Clone the repository:
2. Open the project folder.
3. Open `index.html` in your browser.

No server is required since this is a front-end only project.

## Customization

You can easily modify the project by:

- Adding new songs to the array in `script.js`
- Replacing cover images
- Adjusting the UI in `style.css`
- Extending the player with new features (shuffle, repeat, playlists, etc.)

## Future Improvements

- Add playlist management
- Add volume control
- Add dark/light theme toggle
- Improve animations and loading states
- Mobile responsiveness refinements
- Backend integration for real song streaming

## License

This project is open source and available under the MIT License.

