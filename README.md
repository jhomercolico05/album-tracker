<h1>Album Tracker</h1>   

Album-tracker is a music discovery and collection app, which allows you to search for any album, get personalized recommendations, and maintain a personal library of everything you listen to. When you find an album you can save it to your collection, and rate it yourself, creating a record of your tastes, and recommends album based on your music album collection. There is built-in Deezer integration, so you can browse Deezer’s catalog, pull in album details and artwork and start listening without leaving the app. 

<img width="1919" height="968" alt="image" src="https://github.com/user-attachments/assets/307bc4a3-f451-42d3-9b6d-6d451d7ddd63" />

<img width="1920" height="968" alt="image" src="https://github.com/user-attachments/assets/82b08010-0c3d-4a74-a386-79492d757484" />

<img width="1920" height="966" alt="image" src="https://github.com/user-attachments/assets/e62ce573-3f43-4fab-a87c-73ee4256d471" />

<h3>Link: https://album-tracker-jhomer.vercel.app</h3>

## Features

- **Search** for any album or artist using the iTunes Search API
- **Recommendations** powered by Gemini, based on albums you've saved and rated
- **Save and rate** albums to build a personal collection
- **Preview tracks** with 30-second clips
- **Deezer option** to browse and play from Deezer's catalog

## Tech Stack

- React with Vite
- Context API for state management
- iTunes Search API
- Deezer API
- Google Gemini API
- Vercel for deployment

## Running Locally

1. Clone the repository:
   git clone https://github.com/your-username/album-tracker.git
   cd album-tracker
2. Install dependencies:
   npm install
3. Create a `.env.local` file in the project root and add your Gemini API key:
   VITE_GEMINI_API_KEY=your_key_here
4. Start the dev server:
   npm run dev

## Limitations

- Previews are limited to 30 seconds.
- Your collection is saved only in your browser (local storage), so it won't sync across devices and will be lost if you clear your browser data.
- Deezer requires you to log in to play full tracks.

## Privacy Note

The recommendation feature sends information about your saved albums (such as titles, artists, and ratings) to Google's Gemini API to generate suggestions. Don't include anything in your collection you wouldn't want processed by a third-party AI service. No account is required, and your collection itself is stored only in your browser.

## Disclaimer

This project is for educational purposes and is not affiliated with, endorsed by, or sponsored by Apple, Spotify, Deezer, or Google. All trademarks and album artwork belong to their respective owners.


