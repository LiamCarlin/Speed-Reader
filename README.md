# Speed Reading App

This is a web-based speed reading application that allows users to upload text or PDF files, display words one at a time at a chosen speed, and generate automatic summaries using the OpenAI API.

## Prerequisites

- A modern web browser
- (Optional) A local development server such as [http-server](https://www.npmjs.com/package/http-server) if you want to serve the files over HTTP (required for PDF.js to work properly)

## Setup

1. **Clone the Repository**

   ```sh
   git clone <repository_url>
   cd speed_reading_app
   ```

2. **Configure API Key (Optional)**

   If you plan to use the OpenAI API for generating summaries, update the `config.js` file with your API key and preferred settings. Otherwise, the app will use a simple summary fallback.

   - Open `config.js` and replace `'YOUR_CHATGPT_API_KEY_HERE'` with your actual API key.

3. **Install a Local Server (Optional but Recommended)**

   If you need a local server, install [`http-server`](https://www.npmjs.com/package/http-server):

   ```sh
   npm install -g http-server
   ```

## Running the App

1. **Using a Local Server:**

   From the `speed_reading_app` directory, start the server:

   ```sh
   http-server -c-1
   ```

   Then open your browser at [http://localhost:8080](http://localhost:8080).

2. **Or Open Directly in a Browser:**

   You can also open `index.html` directly, but note that some features (e.g., PDF.js library) might work better over HTTP.

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