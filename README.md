<p align="center">
  <img src="http://checkthese.com/img/IMG_0160.PNG?3" alt="Gospel Audio Messages" width="200" height="200">
</p>

# Gospel Audio Messages


This repository contains a simple web application for sharing and listening to gospel audio messages. It features a clean, responsive design with a toggleable light/dark theme and downloadable audio files.
Features
Responsive Design: Built with Bootstrap, ensuring compatibility across devices.

Theme Toggle: Switch between light and dark themes with a single click.

Audio Playback: Embedded audio players for easy listening directly in the browser.

Downloadable Files: Buttons to download audio messages with error handling.

Custom Styling: CSS variables for easy theme customization.

Installation
To use this project locally or deploy it:
Clone the repository:
bash

git clone https://github.com/your-username/gospel-audio-messages.git

Navigate to the project directory:
bash

cd gospel-audio-messages

Open index.html in a web browser or serve it using a local server (e.g., with Python):
bash

python -m http.server 8000

Then visit http://localhost:8000.

No additional dependencies are required beyond a modern web browser, as Bootstrap is loaded via CDN.
Usage
Open the Page:
Launch index.html in your browser to view the gospel messages.

Interact with Features:
Click the "Toggle Theme" button (top-right) to switch between light and dark modes.

Use the audio players to listen to messages.

Click "Download" buttons to save audio files locally.

Customize (Optional):
Edit the :root and .light-theme CSS variables in the <style> section to adjust colors.

Add more audio messages by duplicating the <div class="col"> blocks in the HTML.

Code Explanation
The project uses HTML, CSS, and JavaScript:
HTML: Structures the page with a navbar, theme toggle, and audio cards.

CSS: Utilizes CSS variables and Bootstrap for theming and responsiveness.

JavaScript:
toggleTheme(): Switches between light and dark modes by toggling a class.

Download functionality: Uses fetch to retrieve audio files as blobs, creating downloadable links with error handling.

Audio files (e.g., Blindfolded Fools.mp3) are assumed to be in an audio/ directory relative to index.html. Update paths if your structure differs.
Contributing
Contributions are welcome! Feel free to submit a Pull Request or open an Issue with suggestions, bug reports, or new features (e.g., adding more messages or enhancing the UI).
License
This project is licensed under the MIT License - see the LICENSE file for details.
Acknowledgments
Built with Bootstrap 5.3.2 for responsive design.

Inspired by the desire to share gospel messages in an accessible, user-friendly format.

Additional Notes:
Ensure audio files are placed in an audio/ folder or adjust the <source src> paths accordingly.

Replace the placeholder image URL in the README with a relevant logo or screenshot of your project.

