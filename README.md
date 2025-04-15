# Fab Auto Claimer Bookmarklet

This is a lightweight, browser-based tool that enables users to add all currently free assets from the Fab Marketplace to their personal library, without requiring any installations or browser extensions.

## Features

- Loops through all available pages on the Fab Marketplace
- Detects free assets using their startingPrice metadata
- Uses authenticated session to perform "Add to Library" actions
- Injects a GUI panel directly into the browser for simple control
- Logs all additions and failures to a live scrollable panel
- Includes performance optimizations and error handling

## Usage Instructions

1. Open `bookmarklet.html` in your browser.
2. Drag the link from the page into your bookmarks bar.
3. Go to [https://www.fab.com](https://www.fab.com) and ensure you are logged in.
4. Click the saved bookmarklet in your bookmarks bar.
5. A panel will appear in the top-right of the page. Click "Start" to begin adding free assets.

The tool will continue scanning and adding until no more pages are available.

## File Descriptions

- `bookmarklet.html`: A web page containing a drag-and-drop link to run the tool as a bookmarklet.
- `bookmarklet.txt`: The compressed JavaScript source that can be copy-pasted directly into a new bookmark URL field.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
