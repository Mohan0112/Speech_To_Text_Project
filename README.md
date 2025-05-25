# Speech to Text Web Application

A web-based application that converts speech to text using the Web Speech API. This application supports multiple languages and provides features for recording, downloading, and clearing transcribed text.

## Features

- Real-time speech to text conversion
- Support for multiple languages
- Download transcribed text as a file
- Clear text functionality
- Modern and responsive UI

## Technologies Used

- HTML5
- CSS3
- JavaScript
- Web Speech API

## Setup and Installation

1. Clone the repository:
```bash
git clone [your-repository-url]
```

2. Open the project folder and run it using one of these methods:

   **Using VS Code Live Server:**
   - Install VS Code
   - Install "Live Server" extension
   - Right-click on `index.html` and select "Open with Live Server"

   **Using Node.js:**
   ```bash
   npm install -g http-server
   http-server
   ```

   **Using Python:**
   ```bash
   python -m http.server 8000
   ```

3. Open your browser and navigate to:
   - For Live Server: `http://127.0.0.1:5500`
   - For http-server: `http://localhost:8080`
   - For Python server: `http://localhost:8000`

## Usage

1. Select your preferred language from the dropdown menu
2. Click the "Start Listening" button
3. Allow microphone access when prompted
4. Speak into your microphone
5. The transcribed text will appear in the result area
6. Use the "Clear" button to remove the text
7. Use the "Download" button to save the text as a file

## Browser Compatibility

This application works best in modern browsers that support the Web Speech API, particularly:
- Google Chrome
- Microsoft Edge
- Firefox
- Safari

## License

This project is open source and available under the MIT License. 