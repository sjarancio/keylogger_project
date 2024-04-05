## Disclaimer
This project is meant for informational and research use only. Use it responsibly and ensure that you have permission to monitor keystrokes on the target system.

# Keylogger Project details
This project showcases a simple keylogger implemented in Python. A keylogger is a tool that captures and records keystrokes made by a user on a computer keyboard. It can be utilized for various purposes including monitoring user activity, debugging software, or as a part of cybersecurity research.

## Features
- Records keystrokes in the background without the user's knowledge.
- Saves captured keystrokes to a txt file for later analysis.
- Lightweight and easy to use.

## Installation and use
1. Clone the repository: git clone https://github.com/sjarancio/keylogger_project.git
2. Navigate to the project directory: cd keylogger
3. Run the following commands to install the required packages:
    - pip3 install pynput
    - pip3 install logging
4. Run the keylogger:
    - python main.py

## Results
- The keylogger will start running silently in the background, it is currently set up to capture all keystrokes on your own machine while the script runs.
- To stop the keylogger, press `Ctrl + C` in the terminal.
- The captured keystrokes will be saved to a log file (`keyLog.txt` by default) and capture each keystroke along with a timestamp for it.
