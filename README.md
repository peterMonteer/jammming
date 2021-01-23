## Jammming

Jammming is a single page React app that interacts with the Spotify API to search for tracks and create a custom playlist in your account! It was developed as part of the Web Development career path at Codecademy.

The app boilerplate was created via the Node.js create-react-app command which abstracts away preprocessing (via Babel) and bundling (via Webpack) automatically. 

## Functions

The user will be redirected to the Spotify login page when he first tries to use the app. After a successfull authentication the app will continue with it's intended behavior.

The search bar allows to search for songs available on Spotify, which will be displayed in the section title "Search Results". These songs can be added to the "Playlist" section using the plus button. The playlist name can also be changed. When done, the user can click the 'save to Spotify' button to send a POST request to the Spotify API.
