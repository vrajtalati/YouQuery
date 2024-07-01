# YouTube Video Content Query System

This project allows users to get answers about the content of YouTube videos without actually watching them. It achieves this by downloading the video, extracting audio, transcribing the audio to text, and then using a language model to answer questions based on the transcribed content.

## Features

- Download YouTube videos.
- Extract audio from the videos.
- Transcribe audio to text using OpenAI's Whisper model.
- Query the transcribed text to get answers about the video's content using OpenAI's GPT-3.5 model.

## Libraries Used

- `pytube`: For downloading YouTube videos.
- `moviepy`: For extracting audio from video.
- `pydub`: For audio processing.
- `openai`: For interaction with OpenAI's GPT-3.5 model.
- `langchain`: For handling language model-based tasks.
- `SpeechRecognition`: For speech-to-text conversion (not explicitly shown in the code, but relevant for similar tasks).

## Getting Started

### Prerequisites

- Python 3.7 or higher
- OpenAI API key

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/youtube-video-content-query-system.git
    cd youtube-video-content-query-system
    ```

2. Install the required libraries:

    ```bash
    pip install pytube moviepy pydub openai langchain SpeechRecognition
    ```

3. Set up your OpenAI API key:

    ```python
    openai_api_key = "your_openai_api_key_here"
    ```

