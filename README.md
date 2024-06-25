# Voice Transcription and Translation Web App

## Overview

This web application allows users to transcribe and translate their voice recordings or uploaded MP3 files. The app is built with React and styled using Tailwind CSS. It leverages machine learning models to perform transcription and translation, specifically using OpenAI's Whisper model for transcription and Xenova's NLLB-200-Distilled-600M model for translation.

## Features

-   **Voice Recording Transcription**: Record your voice and get the transcription in real-time.
-   **MP3 Upload Transcription**: Upload MP3 files and receive a transcription of the audio.
-   **Translation**: Translate the transcribed text into various languages.
-   **English Transcription**: Currently supports only English transcription with plans to add more languages in the future.

## Technologies Used

-   **Frontend**: React, Tailwind CSS
-   **Transcription Model**: [OpenAI Whisper](https://github.com/openai/whisper)
-   **Translation Model**: [Xenova NLLB-200-Distilled-600M](https://huggingface.co/Xenova/nllb-200-distilled-600M)

## Live Link
https://voicescroll.vercel.app/

## Deploying In Your Local Machine

### Prerequisites

-   Node.js (v14 or later)
-   npm (v6 or later)

### Installation

1.  Clone the repository:

`git clone https://github.com/jericho909/voicescroll.git` 

2.  Install the dependencies:


`npm install` 
 

### Running the Application

To start the development server, run:

`npm run dev` 

The app will be available at `http://localhost:3000`.

### Building for Production

To create a production build, run:

`npm run build` 

The production-ready files will be in the `build` directory.


## Roadmap

-   Add support for transcribing additional languages (*transcription only works in English for now*).
-   Improve user interface and user experience.
-   Implement user authentication and save transcriptions for logged-in users.


## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgements

-   [OpenAI Whisper](https://github.com/openai/whisper) for the transcription model.
-   [Xenova NLLB-200-Distilled-600M](https://huggingface.co/Xenova/nllb-200-distilled-600M) for the translation model.
