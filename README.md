# Translator: A Chrome Extension for Text Translation

## Overview

**Translator** is a Chrome extension that allows users to type text and get translations directly in their browser. With a straightforward interface, this extension makes it easy to translate text between various languages while browsing the web.

![Project Screenshot](screenshot.jpg)

## Technologies Used

- **JavaScript**: For handling user interactions, managing translation requests, and updating the extension interface.
- **Chrome Extensions API**: For integrating the translation functionality within the Chrome browser.
- **Translation API**: Utilized to perform the actual text translations.
- **HTML/CSS**: For structuring and styling the extension's popup interface.

## Features

- **Text Translation**: Type text into the extension popup to translate it into the selected language.
- **Language Selection**: Choose from a list of supported languages for translation.
- **Browser Integration**: Access translation functionality directly from the Chrome toolbar.

## Installation

1. Clone this repository:
    ```bash
    git clone https://github.com/vwdr/Translator.git
    ```
2. Navigate to `chrome://extensions/` in your Chrome browser.
3. Enable "Developer mode" by toggling the switch in the top right corner.
4. Click "Load unpacked" and select the directory where you cloned the repository.
5. The extension will be added to your Chrome browser.

## Usage

1. Click on the Translator extension icon in the Chrome toolbar to open the popup.
2. Enter the text you want to translate into the input field.
3. Select the target language from the dropdown menu.
4. Click the "Translate" button to receive the translated text within the extension popup.

## What I Learned

- **Chrome Extensions API**: Integrated the extension into Chrome and managed interactions with the browser environment.
- **API Integration**: Utilized a translation API to handle text translation requests and display results.
- **JavaScript Functionality**: Developed the core functionality for text input, language selection, and displaying translations.
- **User Interface Design**: Created a clean and functional popup interface using HTML and CSS.

## Development

1. **Chrome Extension Structure**: Set up the extension manifest and background scripts to integrate with Chrome.
2. **HTML/CSS Popup**: Designed the popup interface for user interactions, including text input and language selection.
3. **JavaScript Implementation**: Managed API requests, handled user inputs, and updated the popup with translation results.

### Challenges

- **API Key Management**: Secured API keys and ensured they are properly handled within the extension.
- **Browser Integration**: Addressed issues related to extension permissions and interactions with the Chrome browser.
- **User Interface**: Ensured that the extension interface is responsive and user-friendly across different devices.

## Future Improvements

- **Additional Features**: Add functionality for translating text from selected portions of web pages.
- **Language Expansion**: Support more languages and dialects for translation.
- **User Preferences**: Implement settings for saving user preferences and frequently used languages.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes. For bug reports or feature requests, open an issue on GitHub.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
