# Our Little World

A tiny browser co-op room for two people. It is a static website, so it can be hosted on GitHub Pages.

## Run it

Open `index.html` through a local web server, or publish the folder with GitHub Pages. Opening the file directly can work for the artwork, but a web server is recommended for multiplayer.

For a quick local server with Python:

```text
python -m http.server 8000
```

Then open `http://localhost:8000` in a browser.

## Play together

1. One person opens the game and clicks **Create a room**.
2. Share the six-character room code.
3. The other person opens the same website, enters the code, and clicks **Join**.
4. Move with WASD or the arrow keys. On phones, drag the joystick.

The room uses a direct browser-to-browser connection through PeerJS for signaling. No game server or database is required for this first version.

## Publish on GitHub Pages

1. Create a new GitHub repository.
2. Upload `index.html`, `README.md`, and the `assets` folder.
3. In the repository, open **Settings → Pages**.
4. Choose **Deploy from a branch**, select the main branch and the root folder, then save.
5. Open the generated GitHub Pages address on both devices.

Keep the GitHub Pages address on `https://` when playing online.
