# Voice Based Chat Assistant

Voice Based Chat Assistant is a Node.js application that enables voice interactions with an AI assistant using OpenAI's API. The application records audio via a microphone, transcribes it into text, generates a response using OpenAI, and converts the response into speech for playback.

## Features

- **Voice-based interaction** with an AI assistant.
- **Real-time transcription** of audio input.
- **Text-to-speech (TTS)** response from the assistant.
- **Simple command-based control** to start and stop recording.

## Requirements

- **Node.js** v16.0.0 or later.
- **FFmpeg** installed and accessible in your system's PATH.
- **A valid OpenAI API key**.

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/forkyFor/voice_based_chat_assistant.git
   cd voice_based_chat_assistant
   ```

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Configure the OpenAI API key:**

   - Create a `.env` file in the project's root directory.
   - Add your OpenAI API key in the following format:

     ```
     OPENAI_API_KEY="YOUR_OPENAI_API_KEY"
     ```

## Usage

1. **Start the application:**

   ```bash
   node ttsChat.js
   ```

2. **Interact with the assistant:**

   - Press `Enter` to start recording.
   - Speak into the microphone.
   - Press `Enter` again to stop recording.
   - The assistant will transcribe your speech, generate a response, and play it back.

## Dependencies

This project uses the following Node.js packages:

| Package            | Description                                        |
|--------------------|----------------------------------------------------|
| `node-microphone` | Captures audio from the microphone                 |
| `fs`             | File system operations                              |
| `fluent-ffmpeg`  | Handles audio processing                            |
| `ffmpeg-static`  | Provides FFmpeg binaries                            |
| `readline`       | Handles user input                                  |
| `axios`          | Performs HTTP requests                              |
| `form-data`      | Manages multipart form data                         |
| `speaker`        | Plays audio output                                  |
| `openai`         | Interfaces with OpenAI’s API                        |
| `dotenv`         | Loads environment variables from a `.env` file      |

## Troubleshooting

- **FFmpeg issues**: Ensure `ffmpeg` is installed and available in your system’s PATH.
- **Microphone not working**: Check system permissions and microphone settings.
- **OpenAI API errors**: Verify your API key and OpenAI account limits.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributions

Contributions are welcome! Feel free to open an issue or submit a pull request.

---

### Author:  
forkyFor | [GitHub](https://github.com/forkyFor)
