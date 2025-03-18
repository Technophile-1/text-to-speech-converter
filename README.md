# Text To Speech Converter Chrome Extension

This project is a Chrome extension that converts text to speech using the Web Speech API. It allows users to enter text, select a voice, and listen to the spoken output directly from the browser.

## Project Structure

```
text-to-speech-converter
├── src
│   ├── background.js        # Background script for managing events
│   ├── popup.html           # HTML structure for the popup interface
│   ├── script.js            # Main JavaScript logic for text-to-speech functionality
│   ├── style.css            # Styles for the popup interface
│   └── icons
│       ├── icon16.png       # 16x16 pixel icon for the extension
│       ├── icon48.png       # 48x48 pixel icon for the extension
│       └── icon128.png      # 128x128 pixel icon for the extension
├── manifest.json            # Configuration file for the Chrome extension
└── README.md                # Documentation for the project
```

## Setup Instructions

1. **Clone the repository** or download the project files to your local machine.

2. **Open Chrome** and navigate to `chrome://extensions/`.

3. Enable **Developer mode** by toggling the switch in the top right corner.

4. Click on the **Load unpacked** button and select the `text-to-speech-converter` directory.

5. The extension should now be loaded and ready to use.

## Usage

1. Click on the extension icon in the Chrome toolbar to open the popup interface.

2. Enter the text you want to convert to speech in the provided textarea.

3. Select a voice from the dropdown menu.

4. Click the **Convert To Speech** button to listen to the spoken output.

5. You can pause and resume the speech using the same button.

## License

This project is open-source and available for modification and distribution under the MIT License.