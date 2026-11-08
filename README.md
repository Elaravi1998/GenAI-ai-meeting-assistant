# 🤝 AI Meeting Assistant

An AI-powered meeting productivity assistant that transforms meeting transcripts into structured summaries, decisions, action items, open questions, and follow-up emails.

## 🚀 Features

- Meeting transcript processing
- Automatic meeting summarization
- Speaker identification from labeled transcripts
- Decision extraction
- Action-item identification
- Task owner identification
- Optional LLM-powered meeting analysis
- Automated follow-up email generation
- JSON and Markdown report generation
- Privacy-conscious local processing

## 🛠️ Technology Stack

- Python
- Jupyter Notebook
- Generative AI
- Large Language Models (LLMs)
- OpenAI-compatible API
- Regular Expressions
- JSON

## 📂 Project Structure

```text
ai-meeting-assistant/
│
├── ai_meeting_assistant.ipynb
├── README.md
├── requirements.txt
├── .env.example
└── .gitignore
```

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/ai-meeting-assistant.git
```

Navigate into the project:

```bash
cd ai-meeting-assistant
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook ai_meeting_assistant.ipynb
```

## 🔑 Optional LLM Configuration

Install the optional OpenAI SDK:

```bash
pip install openai
```

Configure the following environment variables:

```env
OPENAI_API_KEY=your_api_key
OPENAI_BASE_URL=
OPENAI_MODEL=gpt-4.1-mini
```

The project includes a local baseline that works without an API key.

## 🔍 How It Works

1. Loads a meeting transcript.
2. Cleans and normalizes the transcript.
3. Identifies speaker turns when speaker labels are available.
4. Generates meeting summary points.
5. Extracts candidate decisions.
6. Identifies candidate action items and owners.
7. Optionally uses an LLM to improve the meeting minutes.
8. Generates a follow-up email.
9. Exports meeting minutes as JSON and Markdown.

## 📊 Generated Outputs

```text
meeting_assistant_output/
│
├── meeting_minutes.json
└── meeting_minutes.md
```

## 🔮 Future Enhancements

- Real-time meeting transcription
- Audio-to-text conversion
- Speaker diarization
- Zoom and Google Meet integration
- Microsoft Teams integration
- Calendar integration
- Multilingual meeting summaries
- Meeting history and search
- Streamlit web application
- Automated task management integration

## 🔐 Privacy and Responsible AI

- Obtain appropriate consent before processing meetings.
- Use synthetic or de-identified transcripts for demonstrations.
- Do not commit confidential meeting transcripts or API keys.
- Review generated decisions and action items before sharing.
- Follow organizational data-retention and privacy policies.

## ⚠️ Limitations

This starter version accepts transcript text and does not directly record or transcribe audio. Speaker identification depends on transcript labels. AI-generated summaries and action items may contain errors and require human verification.

## 👨‍💻 Author

Developed as a Generative AI and Python portfolio project.

## 📜 License

Add an appropriate license, such as MIT, before publishing.
