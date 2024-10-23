# SpotifyClone
# Spotify-Like Web App

This project is a simple music player web application inspired by Spotify. It plays non-copyright music tracks that are hosted on AWS S3. Users can play, pause, skip tracks, and view song details such as cover art and song title.

## Features

- Play/pause songs from a playlist
- Display song cover and name
- Progress bar that updates with song playback
- Next and previous buttons to switch between songs
- Hosted songs on AWS S3 for internet access

## Getting Started

### Prerequisites

To run this project, you will need:

- A modern web browser (Chrome, Firefox, etc.)
- Internet access (for fetching songs from AWS S3)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/spotify-webapp.git

2. Navigate to the project directory:
    cd spotify-webapp
3. Open index.html in your browser:
    open index.html
AWS Setup
Songs and covers are hosted on AWS S3.
Ensure that the S3 bucket and objects are publicly accessible to allow playback from the web.
Usage
Click the play/pause button to control the song.
Use the next and previous buttons to switch songs.
View the song name and cover while the song plays.
Known Issues
The play/pause functionality may not always work as expected. This issue is being actively worked on.
License
No official license is provided since this is a personal project using non-copyrighted music.

Acknowledgements
NCS (NoCopyrightSounds) for the music used in this project.
AWS for providing storage services.