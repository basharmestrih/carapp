# YouTube Video Upload Automation Bot

This repository contains a Python bot that automates the process of uploading videos to **YouTube Studio** using **Selenium**. The bot reads video files from your local storage, fetches the title and description from Word files, and uploads unlimited videos to your YouTube channel.

---

## 1. Features

- **Automated Video Uploading**: Uses Selenium to interact with YouTube Studio and upload videos.
- **Local Storage Integration**: Reads video files directly from your local storage.
- **Dynamic Title and Description**: Fetches video titles and descriptions from Word files (`.docx`).
- **Unlimited Uploads**: Can upload multiple videos in a single run.
- **User-Friendly**: Easy to configure and run with minimal setup.

---

## 2. How It Works

1. **Reads Video Files**: The bot scans a specified folder on your local storage for video files.
2. **Fetches Metadata**: It reads the title and description for each video from a Word file (`.docx`).
3. **Automates YouTube Studio**: Using Selenium, the bot logs into YouTube Studio, navigates to the upload page, and fills in the video details.
4. **Uploads Videos**: The bot uploads the videos one by one with the corresponding metadata.

---

## 3. How to Use

### Step 1: Clone the Repository
```bash
git clone https://github.com/your-username/youtube-upload-bot.git
cd youtube-upload-bot
python upload_bot.py
