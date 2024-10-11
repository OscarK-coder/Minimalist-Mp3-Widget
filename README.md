# 🎵 React Music Player - Spotify API Integration

This project is a music player built using **React.js** that integrates with the **Spotify API**. The app allows users to search for songs, play music, and browse playlists directly from the Spotify platform. It offers a user-friendly interface inspired by modern music streaming services.

## Features

- **Search Music**: Search for your favorite songs, albums, and artists.
- **Browse Playlists**: Explore playlists and tracks.
- **Play Music**: Stream music directly from Spotify.
- **Responsive Design**: Mobile-friendly, responsive UI.
- **Authentication with Spotify**: Login with your Spotify account to access personalized features.
- **Player Controls**: Play, pause, skip, and adjust volume.

## Demo

[![Demo Video](https://user-images-url.com)](https://your-live-demo-link.com)

## Screenshots

![Home Screen](https://link-to-screenshot1.com)
![Player Screen](https://link-to-screenshot2.com)

## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

- Node.js installed on your local machine.
- Spotify Developer Account for API credentials.
- A modern web browser.

### Spotify API Setup

1. Go to the [Spotify Developer Dashboard](https://developer.spotify.com/dashboard/applications) and create a new app.
2. Note down the **Client ID** and **Client Secret**.
3. Set up your **Redirect URI** in the Spotify app settings (e.g., `http://localhost:3000/callback`).

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/react-music-player-spotify.git


2. Navigate to the project directory:
   ```bash
   cd react-music-player-spotify

3. Install the dependencies:
   ```bash
   npm install
   
4. Create a .env file in the root of project to add Spotify API credentials:
   ```bash
   REACT_APP_SPOTIFY_CLIENT_ID=your_client_id
   REACT_APP_SPOTIFY_CLIENT_SECRET=your_client_secret
   REACT_APP_SPOTIFY_REDIRECT_URI=http://localhost:3000/callback

5. Start the development server
   ```bash
   npm start
   
6.Open http://localhost:3000 in your browser to see the app.

### Technologies Used
- **React.js**: Frontend library.
- **Spotify Web API**: For fetching music data.
- **Axios**: For making HTTP requests.
- **React Router**: For handling navigation.
- **CSS/SCSS**: For styling the app.
- **Node.js**: For the development environment.
- **Spotify Auth**: OAuth authentication with Spotify.

### License
This project is licensed under the MIT License.

### Acknowledgments
- Spotify for Developers for the API.
- Open-source libraries used in this project.
