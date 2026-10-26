# Online JSON Viewer

A lightweight, browser-based JSON viewer and formatter implemented as a single HTML file with no external dependencies.

## Features

- View and edit JSON in plain text mode
- Format (pretty print) JSON
- Remove whitespace (minify) JSON
- Interactive tree viewer
- Expand and collapse JSON nodes
- Expand all / Collapse all actions
- Load JSON from local files
- Copy and paste JSON using the clipboard
- No server required
- No third-party libraries
- Entire application contained in a single HTML file

## Screenshot

Open in browser https://psanilp.github.io/jsonviewer/

## Usage

### Open Locally

Simply download or clone the repository and open:

```text
index.html
```

in any modern browser.

No installation or build process is required.

### Online

The application can also be hosted using GitHub Pages.

Example URL:

```text
https://psanilp.github.io/jsonviewer/
```

## Working with JSON

### Format JSON

1. Paste or load JSON into the Text tab.
2. Click **Format**.
3. The JSON will be indented and formatted for readability.

### Minify JSON

1. Paste or load JSON.
2. Click **Remove white space**.
3. The JSON will be compressed into a single line.

### Tree View

1. Switch to the **Viewer** tab.
2. Browse the JSON hierarchy.
3. Click ▼ and ▶ icons to expand or collapse nodes.
4. Use **Expand all** or **Collapse all** for large documents.

### Load a File

1. Click **Load JSON data**.
2. Select a `.json` file from your computer.
3. The contents are loaded directly into the editor.

## Technology

- HTML5
- CSS3
- Vanilla JavaScript

No frameworks, build tools, package managers, or backend services are used.

## Browser Support

Tested on modern browsers including:

- Microsoft Edge
- Google Chrome
- Firefox
- Safari

## Privacy

All processing occurs entirely within the browser.

No data is uploaded, transmitted, or stored remotely.


## License

MIT License
