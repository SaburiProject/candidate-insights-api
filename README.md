# Candidate Insights API

An AI-driven backend service that automates interview transcription and HR evaluation using FastAPI, Google Drive API, and OpenAI's GPT-4.

## 🔧 Features

- 🎙️ Transcribes MP3 audio files using OpenAI Whisper
- 📁 Downloads audio from Google Drive
- 📄 Generates HR-style evaluation reports with GPT-4
- 🧠 Uses custom prompts for contextual analysis
- ☁️ Deployable to Cloud Run

---

## 🚀 API Endpoints

### `/transcribe`  
**POST**  
Transcribes an MP3 file from Google Drive  
```json
{
  "file_id": "your_google_drive_file_id"
}
