# My First Remote Keylogger

## Overview

This project is a basic implementation of a remote keylogger. It is designed to capture keystrokes, clipboard data, screenshots, and microphone audio from the target machine. The captured data is then transferred via email to a specified recipient.

**WARNING**: This project is intended for educational purposes only. Unauthorized use of keyloggers and similar software is illegal and unethical. Always obtain explicit consent from the user before deploying this software on any system.

## Features

- **Keystroke Logging**: Records all keystrokes made on the target machine.
- **Clipboard Monitoring**: Captures the content copied to the clipboard.
- **Screenshot Capture**: Periodically takes screenshots of the target machine's screen.
- **Microphone Recording**: Records audio from the target machine's microphone.
- **Email Transfer**: Sends the captured data to a specified email address.

## Prerequisites

- Python 3.x
- Internet connection for email transfer
- Dummy disposable Email account for receiving logs

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/Krithik-sri/keyloggerv1.git
   ```
2. Navigate to the project directory:
   ```bash
   cd keyloggerv1
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Edit the `config.py` file to set your email address and other configurations:
   ```python
   EMAIL_ADDRESS = "your-email@example.com"
   EMAIL_PASSWORD = "your-email-password"
   ```
2. Run the keylogger:
   ```bash
   python keylogger_pyv1.py
   ```

## Acknowledgements

- Thanks to the open-source community for the libraries and tools that made this project possible.
