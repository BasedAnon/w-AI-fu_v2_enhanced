# w-AI-fu v2

A modular framework for building and customizing talking AI Vtuber personalities.

## Key Features

- 🗣️ **Text-to-Speech**: Multiple TTS providers supported for character voices
- 🧠 **Large Language Models**: Different LLM providers for character personalities
- 🎭 **Character Management**: Create and switch between multiple AI characters
- 🎮 **VTube Studio Integration**: Live 2D character animations
- 🎤 **Voice Input**: Optional speech-to-text for talking with your AI
- 💬 **Livestream Integration**: Connect to Twitch chat
- 🛠️ **Extensible**: Modular design for adding new capabilities

## Requirements

- Windows, macOS, or Linux with a modern web browser
- [Node.js](https://nodejs.org/) 18.x or higher
- [Python](https://www.python.org/downloads/) 3.9 or higher (3.10 recommended)
- For voice input: Working microphone and audio output

## Installation

1. **Install Python 3.10** (recommended):
   Download from [python.org](https://www.python.org/downloads/release/python-31011/)

2. **Run the installer**:
   ```
   INSTALL.bat (Windows)
   ./INSTALL.sh (macOS/Linux)
   ```

3. **Launch the application**:
   ```
   RUN.bat (Windows)
   ./RUN.sh (macOS/Linux)
   ```

## API Authentication

### Using NovelAI

w-AI-fu supports two methods for NovelAI authentication:

#### API Key (Recommended)
1. Log in to your NovelAI account at [novelai.net](https://novelai.net/)
2. Go to Account → API Key
3. Generate an API key
4. In w-AI-fu settings, paste the key in the "API Key" field and enable "Use API Key"

#### Username/Password
Simply enter your NovelAI login credentials in the w-AI-fu settings.

### Enhanced NovelAI API

w-AI-fu now includes an enhanced direct Python API implementation for improved reliability:

1. In the w-AI-fu settings, check "Use Enhanced API"
2. This option provides better error handling and connection management
3. Works with both API key and username/password authentication

See [Enhanced_NovelAI_API.md](docs/Enhanced_NovelAI_API.md) for more details.

## Audio Setup

### PyAudio Installation

If you encounter issues with PyAudio installation:

1. Download the appropriate wheel file for your Python version from [PyAudio wheels](https://www.lfd.uci.edu/~gohlke/pythonlibs/#pyaudio)
2. Install manually: `pip install [path-to-downloaded-wheel-file]`

### Audio Output Device

Configure your audio output device in the Settings → Devices tab.

## Customization

w-AI-fu is built for customization. You can:

- Create new characters with unique personalities
- Configure LLM parameters for different response styles
- Adjust voice settings for each character
- Create your own plugins using the modular system

## Documentation

For more detailed information, see the [docs](docs/) directory.

## License

This project is licensed under the [MIT License](LICENSE).