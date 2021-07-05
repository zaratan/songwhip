# Alfred - Songwhip workflow

This workflow allow you to share from various apps (for now Sporitfy and Apple Music) with [Songwhip](songwhip.com)

## From Apple Music

Since Apple Music app doesn't have an easy way to share music, we use the sportify search API to fetch a sharable link => Songwhip

But for this you need Spotify API keys.

Sign up (or in) and create an 'Application' at:
https://developer.spotify.com/my-applications/#!/applications/create

Once you've created your app, find the entries 'Client ID' and 'Client Secret'
You can always get back to your apps at:
https://developer.spotify.com/my-applications/#!/applications

Copy them into `~/.shpotify.cfg` in this format:
```
CLIENT_ID="XXX"
CLIENT_SECRET="YYY"
```
