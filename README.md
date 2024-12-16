# YouTube Assistant App

This application serves as a personal assistant for YouTube, providing enhanced functionalities to improve user experience.

## Features

- **Video Summarization**: Generates concise summaries of YouTube videos.
- **Keyword Extraction**: Identifies and highlights key topics discussed in videos.
- **Transcript Analysis**: Processes video transcripts to extract meaningful insights.

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/youtube-assistant.git
   cd youtube-assistant
    ```

## Set up a virtual env

There's an environment.yml file from which you create a conda env.
   ```bash
conda env create -n youtube-assistant-env -f environment.yml
   ```
Then activate the virtual conda env:
   ```bash
conda activate youtube-assistant-env
   ```

## Local user interface with streamlit:
Run the following command to launch the youtube assistant user interface on your browser:
   ```bash
streamlit run main.py
   ```
   Click on the link that appears on your terminal: you're all set to get summaries of your favorite youtube videos!