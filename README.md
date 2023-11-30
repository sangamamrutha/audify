# audify.github.io
Click here to see the demo : [Audify](https://sangamamrutha.github.io/audify.github.io/)


The project is a web application that performs real-time speech-to-text conversion. Users can speak into their microphone, and the application will transcribe their speech into text. The interface is designed to be user-friendly, with a clean layout and intuitive controls.

Technologies Used:
  - HTML5 for structuring the web page
  - CSS for styling
  - JavaScript for dynamic behaviour, language selection, and handling speech recognition.

Libraries and APIs:
  - Ionicons library (version 5.5.2) for including icons in the UI.
  - Web Speech API for speech recognition functionality.

Key Features:
1. Language Selection:
   - Users can choose their preferred input language from a list of options.
   - The language options are dynamically populated using JavaScript.

2. Recording Interface and Speech Recognition:
   - The main functionality is initiated by a "Start Listening" button.
   - The Web Speech API, specifically the SpeechRecognition interface, is employed for real-time speech recognition.
   - As the user speaks, the application dynamically updates the result area, showing both interim and final speech-to-text results.

3. Download and Clear Actions:
   - Users can download the transcribed text as a file.
   - The "Clear" button resets the result area, and the "Download" button is disabled until there is content to download.

Project Significance:
- The project showcases the integration of core web technologies to provide a practical and accessible solution for speech-to-text conversion.
- Potential use cases include transcription services, accessibility features, and language learning tools.
