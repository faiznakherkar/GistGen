# AI Article Summarizer Chrome Extension

A Chrome extension that uses Google's Gemini AI to summarize articles and web content with one click.

## Features

- **Multiple Summary Types**: Choose between brief, detailed, or bullet-point summaries
- **One-Click Summarization**: Extract and summarize content from any webpage
- **Copy to Clipboard**: Easily copy summaries for use elsewhere
- **Smart Text Extraction**: Automatically detects and extracts article content
- **Secure API Key Storage**: Your Gemini API key is stored locally and securely

## Installation

1. **Get a Gemini API Key**
   - Visit [Google AI Studio](https://makersuite.google.com/app/apikey)
   - Create a free API key

2. **Install the Extension**
   - Clone or download this repository
   - Open Chrome and navigate to `chrome://extensions/`
   - Enable "Developer mode" (top right toggle)
   - Click "Load unpacked" and select the project folder
   - The extension icon will appear in your Chrome toolbar

3. **Setup**
   - Click the extension icon for the first time
   - You'll be redirected to the options page to enter your API key
   - Enter your Gemini API key and save

## Usage

1. Navigate to any article or webpage with text content
2. Click the extension icon in your Chrome toolbar
3. Select your preferred summary type:
   - **Brief**: 2-3 sentence summary
   - **Detailed**: Comprehensive summary
   - **Bullets**: 5-7 key points
4. Click "Summarize" and wait for the AI-generated summary
5. Use "Copy" to copy the summary to your clipboard

## Privacy & Security

- Your API key is stored locally in Chrome's sync storage
- Article text is sent directly to Google's Gemini API
- No data is collected or stored by this extension
- Text content is limited to 20,000 characters for processing

## Requirements

- Chrome browser
- Free Google Gemini API key
- Internet connection for API calls

## Contributing

Feel free to submit issues, fork the repository, and create pull requests for any improvements.


**Note**: This extension requires a valid Gemini API key to function. API usage is subject to Google's terms and rate limits.
