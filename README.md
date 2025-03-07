<p align="center">
  <img src="http://checkthese.com/img/IMG_0160.PNG?3" alt="Gospel Audio Messages" width="200" height="200">
</p>

# Gospel Audio Messages

This repository contains a web application for sharing and listening to gospel audio messages, featuring a toggleable light/dark theme, downloadable audio files, and interactive audio waveform visualizations.

## Features

- **Responsive Design:** Built with Bootstrap for all devices.
- **Theme Toggle:** Switch between light and dark modes with one click.
- **Audio Playback:** Play messages directly in your browser with native controls.
- **Interactive Waveforms:** Visualize audio with WaveSurfer.js waveforms that sync with playback.
- **Downloadable Files:** Download audio files easily.
- **Custom Styling:** Adjust colors with CSS variables.

## Installation

- Download the ZIP from GitHub and extract it, then open `index.html` in a web browser.
- Or copy the code directly into your site.
- Ensure the following dependencies are available (loaded via CDN):
  - [Bootstrap 5.3.2](https://getbootstrap.com/)
  - [WaveSurfer.js 7](https://wavesurfer.js.org/)

## Usage

1. **Open the Page:**
   - Load `index.html` in your browser.
2. **Interact:**
   - Toggle themes with the top-right button.
   - Play or download audio messages using the native player or waveform controls.
   - Click or drag the waveform to seek to any position in the audio.
3. **Customize:**
   - Edit CSS variables in `<style>` or add more audio cards.
   - Update audio file paths in the `<audio>` and WaveSurfer `load()` calls if relocating files.

## Code Explanation

- **HTML:** Sets up the page with navbar, toggle, audio cards, and waveform containers.
- **CSS:** Uses variables and Bootstrap for theming, with styles for waveform containers.
- **JavaScript:** 
  - Toggles themes and handles audio downloads.
  - Integrates WaveSurfer.js for waveform visualization and two-way synchronization with native audio controls.

Audio files (e.g., `Blindfolded Fools.mp3`, `Eyes Wide Shut.mp3`, `Nebula Reverie.mp3`) must be placed in an `audio/` folder—update paths in the code if needed.

## Contributing

Feel free to submit a Pull Request or Issue with suggestions or improvements, especially related to waveform customization or additional features.

## License

MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Built with [Bootstrap 5.3.2](https://getbootstrap.com/).
- Waveform visualization powered by [WaveSurfer.js 7](https://wavesurfer.js.org/).

### Additional Notes:
- Place audio files in `audio/` or adjust `<source src>` paths in `<audio>` tags and `wavesurfer.load()` calls in the JavaScript.
- Replace the image URL with your own logo or a screenshot featuring the waveform (e.g., similar to the one you shared).
- Ensure a stable internet connection for CDN-loaded dependencies (Bootstrap and WaveSurfer.js).

## Screenshot
<p align="left">
  <img src="http://checkthese.com/img/Screenshotgit001.png?1" alt="Gospel Audio Messages" width="600" height="300">
  <img src="http://checkthese.com/img/screenshot_git002.jpg?1" alt="Gospel Audio Messages" width="300" height="600">
  <img src="http://checkthese.com/img/screenshot_git003.jpg?1" alt="Gospel Audio Messages" width="300" height="600">
  <img src="http://checkthese.com/img/screenshot_git004.jpg.png?1" alt="Gospel Audio Messages" width="300" height="600">
  <img src="http://checkthese.com/img/screenshot_git005.jpg.png?1" alt="Gospel Audio Messages" width="600" height="300">
</p>
