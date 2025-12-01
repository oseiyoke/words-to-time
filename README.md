# Words to Time Converter

A simple, beautiful HTML/JS web app that converts word count to estimated reading time.

## Features

- **Real-time conversion**: Instantly calculates reading time as you type or paste text
- **Word counter**: Displays total word count
- **Character counter**: Shows character count including spaces
- **Configurable reading speed**: Adjust words per minute (100-400 WPM) with a slider or preset buttons
- **Reading time estimate**: Converts words to minutes and seconds based on your selected reading speed
- **Clean interface**: Modern, responsive design with gradient background
- **Preset speeds**: Quick access to Slow (150), Average (200), Fast (250), and Very Fast (300) WPM
- **Clear function**: Quick button to clear all text and start over

## Usage

1. Open `index.html` in any modern web browser
2. Paste or type your text in the textarea
3. (Optional) Adjust your reading speed using the slider or preset buttons in the configuration card
4. See the word count, character count, and estimated reading time update automatically
5. Click "Clear Text" to reset

## How It Works

The app calculates estimated reading time based on a configurable reading speed (default: **200 words per minute**). This is based on typical adult reading speeds for standard text.

### Reading Speed Guide:
- **Slow (150 WPM)**: Careful reading, complex material, or non-native language
- **Average (200 WPM)**: Typical adult reading speed for standard text
- **Fast (250 WPM)**: Experienced readers with familiar content
- **Very Fast (300+ WPM)**: Speed reading or skimming

The calculation:
- Total reading time (minutes) = Word count / Words per minute
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
