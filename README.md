# AI Assistant Project

Welcome to the repository for my **AI Assistant project** ! This project is an early-stage voice assistant built using Python and popular libraries like `speech_recognition`, `pyttsx3`, `pywhatkit`, `wikipedia`, and `pyjokes`. The goal of this project is to create a simple voice-controlled assistant that can perform tasks like telling the time, playing songs on YouTube, providing Wikipedia summaries, telling jokes, and more. While the project is functional, it is still a work in progress and requires further development and refinement.

---

## Features (Implemented So Far)

- **Voice Recognition**: The assistant listens to user commands using the microphone and processes them using the `speech_recognition` library.
- **Text-to-Speech**: The assistant responds to user commands by speaking using the `pyttsx3` library.
- **Time Telling**: The assistant can tell the current time when asked.
- **Play Songs on YouTube**: The assistant can play songs on YouTube using the `pywhatkit` library.
- **Wikipedia Summaries**: The assistant can provide brief summaries of topics using the `wikipedia` library.
- **Tell Jokes**: The assistant can tell random jokes using the `pyjokes` library.
- **Basic Search**: If the assistant doesn't understand a command, it performs a web search using `pywhatkit`.

---

## Technologies Used

- **Python**: The core programming language used for the project.
- **SpeechRecognition**: For converting speech to text.
- **pyttsx3**: For converting text to speech.
- **pywhatkit**: For playing songs on YouTube and performing web searches.
- **wikipedia**: For fetching summaries from Wikipedia.
- **pyjokes**: For generating random jokes.
- **datetime**: For fetching and formatting the current time.

---

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/incomplete-voice-assistant.git
   ```
2. Navigate to the project directory:
   ```bash
   cd incomplete-voice-assistant
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the project:
   ```bash
   python voice_assistant.py
   ```
5. Speak commands like:
   - "Alexa, what's the time?"
   - "Alexa, play [song name]"
   - "Alexa, tell me about [topic]"
   - "Alexa, tell me a joke"

---

## Current Limitations

- **Incomplete Error Handling**: The project lacks robust error handling, especially for microphone input issues or unrecognized commands.
- **Basic Functionality**: The assistant currently supports only a few commands and needs more features to be truly useful.
- **No Wake Word Detection**: The assistant processes commands only if they start with "Alexa," but this implementation is basic and can be improved.
- **No GUI**: The project is entirely command-line-based and lacks a graphical user interface (GUI).
- **Limited Customization**: The assistant's voice and behavior are not customizable at the moment.

---

## Planned Improvements

- **Add More Features**: Implement additional functionalities like setting reminders, sending emails, or controlling smart home devices.
- **Improve Wake Word Detection**: Use advanced techniques for wake word detection to make the assistant more responsive.
- **Enhance Error Handling**: Add better error handling for microphone input, internet connectivity, and unrecognized commands.
- **Create a GUI**: Develop a graphical user interface to make the assistant more user-friendly.
- **Optimize Performance**: Improve the efficiency and speed of the assistant's response system.

---

## Contributions

This project is incomplete and open for contributions! If you'd like to help improve this voice assistant, feel free to fork the repository, make changes, and submit a pull request. Some areas where contributions are welcome include:
- Adding new features.
- Improving error handling.
- Enhancing the user interface.
- Optimizing the codebase.

---

Thank you for checking out my incomplete Python AI Assistant project! If you have any questions, suggestions, or feedback, feel free to reach out. Let's make this assistant smarter together! 😊
