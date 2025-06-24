# Candidate Insights API

An AI-driven backend service that automates interview transcription and HR evaluation using FastAPI, Google Drive API, and OpenAI's GPT-4.

## 🔧 Features

- 🎙️ Transcribes MP3 audio files using OpenAI Whisper
- 📁 Downloads audio from Google Drive
- 📄 Generates HR-style evaluation reports with GPT-4
- 🧠 Uses custom prompts for contextual analysis
- ☁️ Deployable to Cloud Run
![image](https://github.com/user-attachments/assets/2b3052d9-320a-47bf-b5f5-71514be4a07c)

---

## 🚀 API Endpoints

### `/transcribe`  
**POST**  
Transcribes an MP3 file from Google Drive  
```json
{
  "file_id": "your_google_drive_file_id"
}
