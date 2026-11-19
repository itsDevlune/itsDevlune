# Optional integrations — Medium + Spotify

These widgets need *your* account identifiers. Their original pasted URLs used `@undefined` for Medium and omitted the required Spotify `user` query parameter. That creates broken images, so they are not enabled in the polished README by default.

## Medium articles

If you actually publish on Medium, replace `YOUR_MEDIUM_HANDLE` below with your Medium username (without `@`) and paste the block into `README.md` **above the Contact section**:

```html
### 📝 Transmissions from my blog

<div align="center">
  <a href="https://medium.com/@YOUR_MEDIUM_HANDLE"><img width="95%" src="https://github-readme-medium-recent-article.vercel.app/medium/@YOUR_MEDIUM_HANDLE/0" alt="Latest Medium article" /></a>
  <a href="https://medium.com/@YOUR_MEDIUM_HANDLE"><img width="95%" src="https://github-readme-medium-recent-article.vercel.app/medium/@YOUR_MEDIUM_HANDLE/1" alt="Second latest Medium article" /></a>
  <a href="https://medium.com/@YOUR_MEDIUM_HANDLE"><img width="95%" src="https://github-readme-medium-recent-article.vercel.app/medium/@YOUR_MEDIUM_HANDLE/2" alt="Third latest Medium article" /></a>
</div>
```

If you have fewer than 3 articles, remove the extra rows.

## Spotify recently played

The Spotify widget needs your connected Spotify account and its `user` value. First authorize/setup your account using the provider instructions: https://github.com/JeffreyCA/spotify-recently-played-readme

Then paste the block below into the README above Contact, replacing `YOUR_SPOTIFY_USER_ID` with the Spotify user ID from the provider setup:

```html
### 🎧 Signals from my playlist

<div align="center">
  <img src="https://spotify-recently-played-readme.vercel.app/api?user=YOUR_SPOTIFY_USER_ID&count=5" width="480" alt="Spotify recently played" />
</div>
```

This is a listening-history image widget, **not a music player**. Its service may be unavailable depending on your account and provider availability.
