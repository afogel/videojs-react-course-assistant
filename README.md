# `videojs-react-course-assistant`

Uses dotenv, please copy the .env.template and to .env and use a valid API key for youtube. Initial load will not fire a youtube request but uses preloaded data.

WIP https://react-coursebuilder.netlify.com/ (env variables not yet set)

## Initial Goals

- [x] Use clean webpack configuration (i.e. no create react app)
- [x] Play with Linaria :D
- [x] VideoJS running okay with context actions
- [x] Use react context for sharing notes and details (probably unnecessary tbh)
- [x] Fetches a youtube playlist with sufficient data (working, needs playlist title)
- [x] Autoplays through playlist
- [x] Takes notes and bookmarks with correct timestamping (context handling added, bookmark = empty note)
- [x] Saves notes relative to a specific playlist to localStorage (should be working once integrated)
- [ ] Mobile view
- [ ] Control panel to control speed and view
- [x] Download notes in a friendly format (csv? Json? what's good?)

## Further afield

See TODO.md

### Notes

- core-js handled to temporarily resolve linaria issues
