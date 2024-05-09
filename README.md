# Mashup
---

# YouTube Audio Mashup Creator

## Overview
This Python script automates the process of downloading specific YouTube videos, converting them into audio format, cutting them to a desired length, and merging them into a single audio file. It's particularly useful for creating mashups or compilations from music videos.

## Features
- **Direct Download**: Downloads YouTube videos directly using their URLs.
- **Audio Conversion**: Converts video files to MP3 format.
- **Audio Trimming**: Trims audio files to a specified duration.
- **Audio Merging**: Merges multiple audio files into one.

## Prerequisites
Before running this script, ensure you have the following installed:
- Python 3.6 or higher
- `pytube` library for downloading YouTube videos
- `moviepy` library for handling video and audio processing

## Installation
To set up your environment to run this script, follow these steps:
1. **Install Python**: Download and install Python from [python.org](https://python.org).
2. **Install Required Libraries**:
   ```bash
   pip install pytube moviepy
   ```

## Usage
To use this script, perform the following steps:
1. **Download the Script**: Clone or download this script into your local machine.
2. **Set Parameters**: Modify the script to include the URLs of the YouTube videos you want to download and the names you want to give them.
3. **Run the Script**: Navigate to the script directory in your terminal and run:
   ```bash
   python mashup_script.py
   ```
   Replace `mashup_script.py` with the name of your Python script file.
4. **Check Output**: After the script finishes running, check the output directory for the merged audio file.

## Configuration
The script allows for various configurations by modifying the following parameters:
- `urls_and_titles`: A list of tuples where each tuple contains a YouTube URL and a custom title for the downloaded video.
- `audio_duration`: The duration to which each audio file should be trimmed, in seconds.
- `output_filename`: The name of the final merged audio file.

## Troubleshooting
If you encounter errors related to video or audio processing, ensure that all dependencies are correctly installed and that you're using the latest versions of `pytube` and `moviepy`.

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments
- [pytube](https://github.com/pytube/pytube): Python library for downloading YouTube Videos.
- [moviepy](https://github.com/Zulko/moviepy): Python library for video editing.

---
