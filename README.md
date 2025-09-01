# TabGist.---AI-Summariser-Chrome-Extension
TabGist is a Chrome Extension that leverages the Google Gemini API to generate concise and accurate summaries of online articles. It allows users to quickly capture the essence of long-form content with options for brief, detailed, or bullet-point summaries.

Features:
- Extracts article text directly from the active page.
- Summarizes content using Google Gemini API.
- Provides multiple summary styles: Brief, Detailed, and Bulleted.
- One-click copy to clipboard.
- Options page for securely saving the Gemini API key.

Project Structure:
TabGist/
│── manifest.json       # Extension configuration  
│── background.js       # Handles installation events  
│── content.js          # Extracts text from web pages  
│── popup.html          # Popup user interface  
│── popup.js            # Summarization logic  
│── options.html        # Options page for API key input  
│── options.js          # API key storage and retrieval  
│── icon.png            # Extension icon  

Installation:
- Clone or download this repository.
- Open chrome://extensions/ in Google Chrome.
- Enable Developer Mode.
- Click Load unpacked and select the project folder.
- Open the Options page and enter your Gemini API key.
- Navigate to any article, open the extension popup, choose a summary type, and click Summarize.

Technologies Used:
- HTML, CSS, JavaScript.
- Chrome Extensions (Manifest V3).
- Google Gemini API.
