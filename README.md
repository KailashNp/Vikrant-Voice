# Vikrant — Voice-Controlled Personal Assistant

Vikrant is a Python-based voice-controlled personal assistant that listens to spoken commands and executes tasks locally on your system. Built from scratch, it combines speech recognition, text-to-speech, and system-level automation into a single lightweight pipeline — no cloud dependency, no subscription, just Python doing the work.

---

## What It Does

- Listens for voice commands in real time
- Opens applications and system tools on command
- Plays media and handles basic entertainment controls
- Retrieves information through voice queries
- Responds back with synthesized speech
- Processes custom voice commands through built-in algorithms

---

## Tech Stack

| Tool | Purpose |
|------|---------|
| Python | Core language |
| SpeechRecognition | Converts speech input to text |
| pyttsx3 | Converts text responses to speech |
| os | System-level control and app launching |

---

## How It Works

1. Vikrant listens through your microphone using SpeechRecognition
2. The audio input is converted to text
3. Custom command processing algorithms parse the intent
4. The corresponding action is executed at the system level
5. A spoken response is returned via pyttsx3

---

## What I Learned

- End-to-end voice pipeline architecture
- API integration and library chaining
- Custom algorithm design for command parsing
- Python system control and automation
- Problem-solving for speech accuracy and performance

---

## Why I Built This

Most voice assistants are cloud-dependent and closed. Vikrant was built to understand what actually happens under the hood — how speech becomes text, how intent gets parsed, and how a program talks back. It was my first real dive into building something that felt alive.

---
