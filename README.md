# Balloons from Belarus

Animated map of balloon and drone airspace disruption between Belarus and
Lithuania, 2025.

## Hosting on GitHub Pages

Commit the contents of this folder to a repository, then enable Pages
(Settings → Pages → Deploy from a branch). Serve from the branch root if these
files are at the top level, or from `/docs` if you move them there.

Files:

    index.html               the visualisation
    support.js               runtime it loads
    assets/relief-a3.png     shaded relief background
    assets/zaxis-logo.svg    logo

All paths are relative, so the folder works from any subdirectory.

Fonts (IBM Plex Sans and IBM Plex Mono) load from Google Fonts. To avoid the
third-party request, download the two families, place them in
`assets/fonts/`, and replace the `<link>` tags in `index.html` with local
`@font-face` rules.

## Local preview

Open `index.html` directly, or serve the folder:

    python3 -m http.server

## Notes

The poster is a fixed 1920 × 1358 canvas at A3 landscape proportions. It does
not reflow for small screens; embed it in a scaling container if that matters.

Data sources are credited in the footer of the visualisation itself.
