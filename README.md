# albums-data

Build output for [albums.siena.codes](https://albums.siena.codes): my album collection as a JSON feed and a cover grid, for displays and widgets. Every file here is generated; the source data lives in a private repo and the build replaces this folder wholesale.

- `albums.json`: `generated`, `counts`, and `albums`, one entry per copy owned with a `cover` path or null.
- `plays.json`: `captured`, `counts`, and `tracks`, my most played songs from Apple Music by play count; owned or not, these are listens, not the shelf.
- `covers/<id>.jpg`: 300px cover per entry.
- `index.html`: the grid.
