# Voice Assistant Using Python

# Overview

This project is a Python-based voice assistant that performs basic tasks such as telling the time, opening applications, and searching Wikipedia. The assistant uses speech recognition and text-to-speech synthesis to interact with the user.

# Features

Voice Commands: Responds to spoken commands.

Application Control: Opens commonly used applications like Chrome and Microsoft Edge.

Time Query: Tells the current time.

Wikipedia Search: Provides a one-sentence summary from Wikipedia.

Personalized Greetings: Welcomes the user based on the time of day.

# Requirements

Ensure you have the following installed on your system:

Python 3.7 or later

Required Python libraries:

pip install pyttsx3 speechrecognition wikipedia pywhatkit pyautogui pyjokes

# Setup Instructions

Clone or Download the Repository:

git clone <https://github.com/knaveen-developer/voice-assistant.git>

cd voice-assistant

Install Dependencies: Use pip to install the required libraries (as mentioned above).

Run the Script: Execute the script in your terminal or IDE:

python assistant.py

# Usage

Start the Assistant:

Run the script, and the assistant will greet you.

Give Commands:

Example commands:

"What is the time?"

"Open Chrome."

"Search Wikipedia for Python programming."

# File Structure

voice-assistant/

│

├── assistant.py # Main script

├── requirements.txt # List of dependencies

└── README.md # Documentation

# Customization

Add Your Own Commands: Modify the elif statements in the commands() function to include additional tasks.

Voice Settings: Change the voice or speech rate in the speak() function.

# Known Issues

Speech recognition may fail in noisy environments.

Some application paths are hardcoded and may need to be updated.

# Future Enhancements

Integration with weather APIs.

Adding reminders and to-do lists.

Improved error handling and support for multiple languages.

## License

This project is licensed under a **Custom License**.

### Terms:

- **Personal use**: You may use the software for personal, non-commercial purposes without any charge.
- **Commercial use**: If you wish to use the software for any commercial purposes (including but not limited to integrating it into your own projects, using it for business purposes, or offering it as a paid service), you are required to purchase a **commercial license**.
- **Redistribution**: Redistribution of the software in any form, modified or unmodified, is strictly prohibited unless you have obtained a **redistribution license** by paying a fee. This applies to both commercial and non-commercial redistribution.

To purchase a **commercial license** or **redistribution rights**, please contact the author at <hustlersnetwork18@gmai.com>. Pricing and terms will be provided upon inquiry.

### Copyright:
Copyright (c) [2025], [Naveen.K/HUSTLERS NETWORK].


# Contributing

Contributions are welcome! If you have suggestions or improvements, please fork the repository and submit a pull request.

# Contact

For questions or feedback, reach out to:

Email: <hustlersnetwork18@gmail.com>
