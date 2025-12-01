# Words to Time Converter

A simple, beautiful HTML/JS web app that converts word count to estimated reading time.

## Features

- **Real-time conversion**: Instantly calculates reading time as you type or paste text
- **Word counter**: Displays total word count
- **Character counter**: Shows character count including spaces
- **Reading time estimate**: Converts words to minutes and seconds based on average reading speed (200 words per minute)
- **Clean interface**: Modern, responsive design with gradient background
- **Clear function**: Quick button to clear all text and start over

## Usage

1. Open `index.html` in any modern web browser
2. Paste or type your text in the textarea
3. See the word count, character count, and estimated reading time update automatically
4. Click "Clear Text" to reset

## How It Works

The app uses an average reading speed of **200 words per minute** to calculate the estimated time. This is based on typical adult reading speeds for standard text.

The calculation:
- Total reading time (minutes) = Word count / 200
- The result is then split into minutes and seconds for easy reading

## Files

- `index.html` - Single-file app with HTML, CSS, and JavaScript

## Browser Support

Works in all modern browsers:
- Chrome
- Firefox
- Safari
- Edge

No dependencies or build process required!
