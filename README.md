# Assistive Technology for Dumb, Blind, and Deaf Individuals 🌐👁️👂🔇

## Introduction
This project aims to develop assistive technology solutions to enhance the lives of individuals who are dumb, blind, and deaf. By leveraging modern technology and innovative design, we seek to empower these individuals by providing tools and resources to improve accessibility, communication, and independence.

## Modules
### Dumb Module:
1. **Text Input**: Users input text via a graphical user interface (GUI) built with `tkinter`.
2. **Text-to-Speech (TTS)**: The entered text is converted into speech using the `gTTS` (Google Text-to-Speech) API.
3. **Audio Output**: The synthesized speech is played through the speakers, allowing users to hear the converted text.

**Flow**:
📝 TEXT → ⌨️ KEYBOARD (Input) -> 📝 TEXT -> 📢 SPEAKER (Output) -> 🔊 AUDIO

### Blind Module:
1. **Image Capture**: The system captures images of text using a camera or webcam.
2. **Text Extraction**: Utilizing Google Cloud Vision API, the captured images are processed to extract text information.
3. **Text-to-Speech (TTS)**: The extracted text is converted into speech using the `gTTS` API.
4. **Audio Output**: The synthesized speech is played through speakers or headphones, enabling users to listen to the content.

**Flow**:
📷 IMAGE → 🎥 CAMERA -> 📝 TEXT -> 📢 SPEAKER (Output) -> 🔊 AUDIO

### Deaf Module:
1. **Audio Input**: Sound is captured through a microphone.
2. **Speech Recognition**: Using a speech recognition API, such as Google Speech API, the captured audio is converted into text.
3. **Display Output**: The recognized text is displayed on a graphical user interface (GUI) built with `tkinter`, providing visual feedback to the user.

**Flow**:
🔊 AUDIO → 🎤 MICROPHONE -> 📝 TEXT -> 🖥️ DISPLAY

These modules utilize various technologies such as `tkinter` for GUI development, `gTTS` for text-to-speech conversion, and APIs like Google Cloud Vision and Speech API for image processing and speech recognition, respectively. By integrating these components, the project aims to provide comprehensive assistive solutions for individuals who are dumb, blind, and deaf.

*Get in Touch:** Use the contact form to connect with me for collaborations or inquiries.
https://forms.gle/vuDnTYrM2ZeeVf8y7
