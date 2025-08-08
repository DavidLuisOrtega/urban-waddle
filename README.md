# AI Chatbot with Text-to-Speech

A modern web-based chatbot that uses OpenAI for responses and ElevenLabs for text-to-speech audio output.

## Features

- **Text Input**: Type messages in a clean chat interface
- **AI Responses**: Powered by OpenAI's GPT-3.5-turbo model
- **Text-to-Speech**: Audio responses using ElevenLabs API
- **Modern UI**: Beautiful, responsive design
- **Secure**: API keys stored locally in browser

## Setup

1. **Get API Keys**:
   - [OpenAI API Key](https://platform.openai.com/api-keys)
   - [ElevenLabs API Key](https://elevenlabs.io/api-key)
   - [ElevenLabs Voice ID](https://elevenlabs.io/voice-library)

2. **Run the Application**:
   ```bash
   # Open index.html in your browser
   open index.html
   ```

3. **Configure API Keys**:
   - Enter your API keys when prompted
   - Keys are saved locally for future use

## Usage

- Type your message and press Enter or click Send
- The AI will respond with text and audio
- Click the "Play Response" button to hear the audio
- Audio automatically converts the AI's text response

## File Structure

```
├── index.html      # Main HTML file
├── styles.css      # CSS styling
├── script.js       # JavaScript functionality
└── README.md       # This file
```

## API Requirements

- **OpenAI**: GPT-3.5-turbo model
- **ElevenLabs**: Text-to-speech conversion
- **Voice ID**: Choose from ElevenLabs voice library

## Browser Compatibility

- Modern browsers with ES6+ support
- Requires internet connection for API calls 