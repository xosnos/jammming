# jammming

A React app for building custom playlists directly to your Spotify account.

## Install & Run

0. Make sure to have the following installed on your computer: `node` & `npm`

1. From terminal, clone the repository: `git clone https://github.com/xosnos/jammming.git`

2. Enter the directory: `cd jammming`

3. Install the dependencies: `npm install`

4. Run the app in development mode: `npm start`

5. Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

## Next Steps

- [ ] Pressing enter triggers a search
- [ ] Include preview samples for each track
- [ ] Only display songs not currently present in the playlist in the search results
- [ ] Add a loading screen while playlist is saving
- [ ] Update the access token logic to expire at exactly the right time, instead of setting expiration from when the user initiates their next search
- [ ] After user redirect on login, restoring the search term from before the redirect
- [ ] Ensure playlist information doesn’t get cleared if a user has to refresh their access token
- [ ] Provide a way to fetch and see all your existing playlists

## Notes

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

Based on Jammming, the React Capstone project from Codecademy's  [Create a front-end app with React](https://www.codecademy.com/learn/paths/build-web-apps-with-react) skill path.
