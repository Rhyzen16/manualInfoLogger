# QRZ Contact Logger

A simple and clean web-based contact logging form for amateur radio operators.  
Built with HTML, Tailwind CSS, and JavaScript, this app allows quick logging of QSOs and sends contact information to a Discord webhook for record-keeping.

## Features

- Clean, mobile-responsive interface
- Automatic UTC datetime fill
- Live character counter for notes
- Instant feedback with toast notifications
- Displays the last submitted contact
- Discord webhook integration for real-time logging
- Tailwind CSS styling via CDN for easy customization

## Demo

No live demo hosted.  
Download the project files and open `index.html` in your browser to try it.

## Usage

1. Download or clone this repository.
2. Update the `webhookUrl` inside the `<script>` section of `index.html` with your own Discord webhook URL.
3. Open `index.html` with any modern web browser.
4. Fill out the form and log your contact!

## Installation

No installation or build process required.  
Just open the `index.html` directly.

## Configuration

- **Webhook URL:**  
  Find this line in the JavaScript:
  
  ```javascript
  const webhookUrl = "YOUR_DISCORD_WEBHOOK_URL_HERE";
