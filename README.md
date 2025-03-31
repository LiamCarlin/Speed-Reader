# Speed Reading App

This is a web-based speed reading application that allows users to upload text or PDF files, display words one at a time at a chosen speed, and generate automatic summaries using the OpenAI API.

## Prerequisites

- A modern web browser
- (Optional) A local development server such as [http-server](https://www.npmjs.com/package/http-server) if you want to serve the files over HTTP (required for PDF.js to work properly)

## Setup

1. **Clone the Repository**

   ```sh
   git clone https://github.com/LiamCarlin/Speed-Reader.git
   cd speed_reading_app
   ```

2. **Install a Local Server (Optional but Recommended)**
If you need a local server, install the [Live Server extension](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) for Visual Studio Code:

1. Open Visual Studio Code.
2. Go to the Extensions view by clicking on the Extensions icon in the Activity Bar on the side of the window.
3. Search for "Live Server" and click "Install."
4. Once installed, open the `index.html` file in your project.
5. Right-click on the editor and select "Open with Live Server."

This will start a local server and open the app in your default browser.

## Files Overview

- **HTML:**  
  `index.html` – Contains the structure and layout of the app.

- **JavaScript:**  
  `main.js` – Implements file uploads, text processing, summary API integration, and speed reading functionality.

- **CSS:**  
  `style.css` – Styles for the app.

- **Configuration:**  
  `config.js` – Stores the ChatGPT API key and related settings.

---

Happy reading!