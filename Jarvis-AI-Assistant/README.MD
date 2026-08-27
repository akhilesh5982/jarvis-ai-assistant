# Jarvis AI Assistant

An intelligent AI-powered project generator and assistant that creates complete web applications using modern technologies.

## 🚀 Features

- **AI-Powered Project Generation**: Creates complete projects with HTML, CSS, and JavaScript
- **Voice Interaction**: Speak to Jarvis and get voice responses
- **Smart Project Planning**: AI generates detailed project plans with file structures
- **Modern Code Generation**: Creates responsive, modern web applications
- **Modular Architecture**: Clean, maintainable code structure

## 📁 Project Structure

```
jarvis-ai-assistant/
├── config/
│   └── config.js          # Configuration settings
├── controllers/
│   └── JarvisController.js # Main application controller
├── models/
│   ├── ProjectPlanner.js  # AI project planning
│   └── FileGenerator.js   # File generation logic
├── services/
│   ├── geminiService.js   # Gemini API integration
│   └── voiceService.js    # Voice input/output
├── utils/
│   └── logger.js          # Logging utilities
├── projectsByJarvis/      # Generated projects directory
├── index.js               # Application entry point
├── package.json
└── README.md
```

## 🛠️ Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd jarvis-ai-assistant
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   ```bash
   # Create .env file
   echo "GEMINI_API_KEY=your-api-key-here" > .env
   ```

4. **Get your Gemini API key**
   - Go to [Google AI Studio](https://makersuite.google.com/app/apikey)
   - Create a new API key
   - Add it to your `.env` file

## 🎯 Usage

### Start Jarvis
```bash
npm start
```

### Available Commands

| Command | Description |
|---------|-------------|
| `create <description>` | Create a new project |
| `list` | List current directory files |
| `open <filename>` | Open and display a file |
| `voice` | Start voice interaction mode |
| `help` | Show all commands |
| `exit` | Exit the application |

### Examples

```bash
# Create a todo app
create todo app with drag and drop

# Create a weather dashboard
create weather dashboard with charts

# Create a fullstack expense tracker
create fullstack expense tracker with React
```

### Voice Mode

Type `voice` to enter voice interaction mode:

- Say "create project [description]" to create projects
- Ask any question for AI responses
- Say "exit voice" to return to text mode

## 🎨 Generated Projects

All projects are created in the `projectsByJarvis/` directory with:

- **Complete file structure** with HTML, CSS, and JavaScript
- **Modern responsive design** with CSS Grid and Flexbox
- **Interactive features** with smooth animations
- **Production-ready code** with best practices
- **Comprehensive documentation** with README files

## 🏗️ Architecture

### Core Components

1. **JarvisController**: Main application logic and user interaction
2. **ProjectPlanner**: AI-powered project planning and structure generation
3. **FileGenerator**: Code generation with templates and fallbacks
4. **GeminiService**: API integration with caching and retry logic
5. **VoiceService**: Voice input/output using Windows SAPI

### Key Features

- **Modular Design**: Clean separation of concerns
- **Error Handling**: Robust error handling with fallbacks
- **Caching**: API response caching to reduce calls
- **Rate Limiting**: Built-in rate limiting for API calls
- **Voice Support**: Windows speech synthesis and recognition

## 🔧 Configuration

Edit `config/config.js` to customize:

- API settings and delays
- Voice configuration
- Project directory location
- Console colors and styling

## 🎤 Voice Features

### Requirements
- Windows 10/11
- Microphone (for voice input)
- Speakers (for voice output)
- Windows Speech Recognition enabled

### Voice Commands
- "Hello" / "Hi" - Get greetings
- "Create project [description]" - Create new projects
- "List files" - Show directory contents
- "Help" - Show available commands
- "Exit voice" - Return to text mode

## 🚀 Development

### Run in development mode
```bash
npm run dev
```

### Project Structure
- `config/`: Configuration files
- `controllers/`: Main application logic
- `models/`: Business logic and data models
- `services/`: External service integrations
- `utils/`: Utility functions and helpers

## 📝 Environment Variables

Create a `.env` file in the root directory:

# Jarvis AI Assistant

An intelligent AI-powered project generator and assistant that creates complete web applications using modern technologies.

## 🚀 Features

- **AI-Powered Project Generation**: Creates complete projects with HTML, CSS, and JavaScript
- **Voice Interaction**: Speak to Jarvis and get voice responses
- **Smart Project Planning**: AI generates detailed project plans with file structures
- **Modern Code Generation**: Creates responsive, modern web applications
- **Modular Architecture**: Clean, maintainable code structure

## 📁 Project Structure

jarvis-ai-assistant/
├── config/
│ └── config.js # Configuration settings
├── controllers/
│ └── JarvisController.js # Main application controller
├── models/
│ ├── ProjectPlanner.js # AI project planning
│ └── FileGenerator.js # File generation logic
├── services/
│ ├── geminiService.js # Gemini API integration
│ └── voiceService.js # Voice input/output
├── utils/
│ └── logger.js # Logging utilities
├── projectsByJarvis/ # Generated projects directory
├── index.js # Application entry point
├── package.json
└── README.md


## 🛠️ Installation

1. **Clone the repository**
```bash
   git clone https://github.com/akhilesh5982/jarvis-ai-assistant.git
   cd jarvis-ai-assistant
```

2. **Install dependencies**
```bash
   npm install
```

3. **Set up environment variables**
```bash
   # Create .env file
   echo "GEMINI_API_KEY=your-api-key-here" > .env
```

4. **Get your Gemini API key**
   - Go to [Google AI Studio](https://makersuite.google.com/app/apikey)
   - Create a new API key
   - Add it to your `.env` file

## 🎯 Usage

### Start Jarvis
```bash
npm start
```

### Available Commands

| Command | Description |
|---------|-------------|
| `create <description>` | Create a new project |
| `list` | List current directory files |
| `open <filename>` | Open and display a file |
| `voice` | Start voice interaction mode |
| `help` | Show all commands |
| `exit` | Exit the application |

### Examples

```bash
# Create a todo app
create todo app with drag and drop

# Create a weather dashboard
create weather dashboard with charts

# Create a fullstack expense tracker
create fullstack expense tracker with React
```

### Voice Mode

Type `voice` to enter voice interaction mode:

- Say "create project [description]" to create projects
- Ask any question for AI responses
- Say "exit voice" to return to text mode

## 🎨 Generated Projects

All projects are created in the `projectsByJarvis/` directory with:

- **Complete file structure** with HTML, CSS, and JavaScript
- **Modern responsive design** with CSS Grid and Flexbox
- **Interactive features** with smooth animations
- **Production-ready code** with best practices
- **Comprehensive documentation** with README files

## 🏗️ Architecture

### Core Components

1. **JarvisController**: Main application logic and user interaction
2. **ProjectPlanner**: AI-powered project planning and structure generation
3. **FileGenerator**: Code generation with templates and fallbacks
4. **GeminiService**: API integration with caching and retry logic
5. **VoiceService**: Voice input/output using Windows SAPI

### Key Features

- **Modular Design**: Clean separation of concerns
- **Error Handling**: Robust error handling with fallbacks
- **Caching**: API response caching to reduce calls
- **Rate Limiting**: Built-in rate limiting for API calls
- **Voice Support**: Windows speech synthesis and recognition

## 🔧 Configuration

Edit `config/config.js` to customize:

- API settings and delays
- Voice configuration
- Project directory location
- Console colors and styling

## 🎤 Voice Features

### Requirements
- Windows 10/11
- Microphone (for voice input)
- Speakers (for voice output)
- Windows Speech Recognition enabled

### Voice Commands
- "Hello" / "Hi" - Get greetings
- "Create project [description]" - Create new projects
- "List files" - Show directory contents
- "Help" - Show available commands
- "Exit voice" - Return to text mode

## 🚀 Development

### Run in development mode
```bash
npm run dev
```

### Project Structure
- `config/`: Configuration files
- `controllers/`: Main application logic
- `models/`: Business logic and data models
- `services/`: External service integrations
- `utils/`: Utility functions and helpers

## 📝 Environment Variables

Create a `.env` file in the root directory:

```env
GEMINI_API_KEY=your-gemini-api-key-here
```

## 🐛 Troubleshooting

- **"GEMINI_API_KEY not found" error**: Make sure your `.env` file is in the root directory and contains a valid key with no extra spaces.
- **Voice mode not working**: Confirm Windows Speech Recognition is enabled in Settings > Time & Language > Speech, and that your microphone has permission to be used by apps.
- **`npm start` fails immediately**: Run `npm install` again to make sure all dependencies were installed correctly, and check that you're using Node.js v16 or higher.
- **API rate limit errors**: Gemini's free tier has request limits; wait a few minutes before retrying, or check your usage on Google AI Studio.

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Add tests if applicable
5. Submit a pull request

## 🙏 Acknowledgments

- Google Gemini API for AI capabilities
- Windows Speech API for voice features
- Node.js community for excellent tooling

## 👨‍💻 Developer Info

- **Maintained by**: Akhilesh
 Indian Institute of Technology (Indian School of Mines) Dhanbad