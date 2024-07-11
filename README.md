# Voice Assistant Using Python

## Overview
This project is a Python-based Voice Assistant similar to popular assistants like Alexa or Siri. It leverages various Python libraries to perform tasks such as speech recognition, text-to-speech conversion, web searches, fetching information from Wikipedia, telling jokes, sending emails, and more.

## Features
- **Speech Recognition**: Converts voice commands to text using the SpeechRecognition library.
- **Text-to-Speech**: Converts text responses to speech using the pyttsx3 library.
- **WolframAlpha Integration**: Provides expert-level answers to queries using WolframAlpha API.
- **Wikipedia Integration**: Fetches summaries from Wikipedia.
- **Web Browser Control**: Opens websites like YouTube, Google, and Stack Overflow.
- **Music Playback**: Plays music from a specified directory.
- **Email Functionality**: Sends emails using the smtplib library.
- **Jokes**: Tells jokes using the Pyjokes library.
- **Weather Updates**: Fetches weather updates using the OpenWeatherMap API.
- **News Updates**: Provides top news updates from the Times of India.
- **Camera Control**: Captures photos using the ecapture library.
- **System Commands**: Executes system commands like shutting down, restarting, and hibernating the system.
- **Customizable Greetings and Names**: Personalizes greetings and can change its own name.

## Requirements
- Python 3.x
- Required Python libraries (install using `pip install <library>`):
  - SpeechRecognition
  - Pyttsx3
  - WolframAlpha
  - Wikipedia
  - Ecapture
  - Pyjokes
  - Requests
  - BeautifulSoup
  - Twilio

## Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/voice-assistant.git
   cd voice-assistant
   ```

2. Install the required libraries:
   ```sh
   pip install -r requirements.txt
   ```

3. Run the assistant:
   ```sh
   python voice_assistant.py
   ```

## Usage
- **Activate the Assistant**: The assistant will greet you and prompt you for commands.
- **Commands**:
  - "Search Wikipedia for [query]"
  - "Open YouTube"
  - "Play music"
  - "Tell me a joke"
  - "What's the weather like?"
  - "Send an email to [recipient]"
  - "Capture a photo"
  - "Shut down the system"

## Contribution
Contributions are welcome! Feel free to open issues or submit pull requests.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements
- Thanks to the developers of the various Python libraries used in this project.
- Special thanks to WolframAlpha, Wikipedia, and other APIs for their data.

---
