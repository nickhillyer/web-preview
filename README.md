# web-preview

A simple, single-file HTML preview tool for viewing and editing HTML code.

## Features

- 📋 **Paste HTML** from clipboard (button or Ctrl+V/Cmd+V)
- 📄 **Copy HTML** to clipboard with visual feedback
- 🔄 **Toggle view** between code and rendered HTML preview
- 📱 **Mobile-friendly** responsive design
- 🎨 **Clean, modern UI** with fixed toolbar
- ⚡ **No dependencies** - pure HTML, CSS, and JavaScript

## Usage

Simply open `index.html` in your browser. The tool provides three main functions:

1. **Paste**: Click the "Paste" button or press Ctrl+V (Cmd+V on Mac) to load HTML from your clipboard
2. **Copy**: Click the "Copy" button to copy the current HTML back to your clipboard
3. **Toggle**: Click the "Toggle View" button to switch between viewing the HTML source code and the rendered preview

## Security Note

This tool renders arbitrary HTML using `innerHTML` to provide preview functionality. Only use it with HTML content you trust, as it will execute any JavaScript contained in the pasted HTML.