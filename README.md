# Lagani Capital - Stock Report

This is a client-side web application that uses the Polygon.io API to fetch stock data and the OpenAI API to generate a stock performance report.

## Setup and Installation

### 1. API Keys

This project requires API keys for both Polygon.io and OpenAI. You must create a file named `api_keys.js` in the root of the project directory.

Create the `api_keys.js` file and add the following content, replacing `"YOUR_KEY_HERE"` with your actual API keys:

```javascript
const OPENAI_API_KEY = "YOUR_KEY_HERE";
const POLYGON_API_KEY = "YOUR_KEY_HERE";
```

**Important**: The `api_keys.js` file is included in `.gitignore` to prevent your keys from being accidentally committed to the repository.

### 2. Running the Application

Because this application uses ES6 modules, it must be served by a local web server. You cannot run it by simply opening `index.html` in your browser.

1.  Navigate to the project directory in your terminal.
2.  Start a simple Python web server:
    ```bash
    python3 -m http.server
    ```
3.  Open your web browser and go to `http://localhost:8000`.
