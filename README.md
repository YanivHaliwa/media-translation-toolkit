# Media Translation Toolkit

[![zread](https://img.shields.io/badge/Ask_Zread-_.svg?style=flat&color=00b0aa&labelColor=000000&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB3aWR0aD0iMTYiIGhlaWdodD0iMTYiIHZpZXdCb3g9IjAgMCAxNiAxNiIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPHBhdGggZD0iTTQuOTYxNTYgMS42MDAxSDIuMjQxNTZDMS44ODgxIDEuNjAwMSAxLjYwMTU2IDEuODg2NjQgMS42MDE1NiAyLjI0MDFWNC45NjAxQzEuNjAxNTYgNS4zMTM1NiAxLjg4ODEgNS42MDAxIDIuMjQxNTYgNS42MDAxSDQuOTYxNTZDNS4zMTUwMiA1LjYwMDEgNS42MDE1NiA1LjMxMzU2IDUuNjAxNTYgNC45NjAxVjIuMjQwMUM1LjYwMTU2IDEuODg2NjQgNS4zMTUwMiAxLjYwMDEgNC45NjE1NiAxLjYwMDFaIiBmaWxsPSIjZmZmIi8%2BCjxwYXRoIGQ9Ik00Ljk2MTU2IDEwLjM5OTlIMi4yNDE1NkMxLjg4ODEgMTAuMzk5OSAxLjYwMTU2IDEwLjY4NjQgMS42MDE1NiAxMS4wMzk5VjEzLjc1OTlDMS42MDE1NiAxNC4xMTM0IDEuODg4MSAxNC4zOTk5IDIuMjQxNTYgMTQuMzk5OUg0Ljk2MTU2QzUuMzE1MDIgMTQuMzk5OSA1LjYwMTU2IDE0LjExMzQgNS42MDE1NiAxMy43NTk5VjExLjAzOTlDNS42MDE1NiAxMC42ODY0IDUuMzE1MDIgMTAuMzk5OSA0Ljk2MTU2IDEwLjM5OTlaIiBmaWxsPSIjZmZmIi8%2BCjxwYXRoIGQ9Ik0xMy43NTg0IDEuNjAwMUgxMS4wMzg0QzEwLjY4NSAxLjYwMDEgMTAuMzk4NCAxLjg4NjY0IDEwLjM5ODQgMi4yNDAxVjQuOTYwMUMxMC4zOTg0IDUuMzEzNTYgMTAuNjg1IDUuNjAwMSAxMS4wMzg0IDUuNjAwMUgxMy43NTg0QzE0LjExMTkgNS42MDAxIDE0LjM5ODQgNS4zMTM1NiAxNC4zOTg0IDQuOTYwMVYyLjI0MDFDMTQuMzk4NCAxLjg4NjY0IDE0LjExMTkgMS42MDAxIDEzLjc1ODQgMS42MDAxWiIgZmlsbD0iI2ZmZiIvPgo8cGF0aCBkPSJNNCAxMkwxMiA0TDQgMTJaIiBmaWxsPSIjZmZmIi8%2BCjxwYXRoIGQ9Ik00IDEyTDEyIDQiIHN0cm9rZT0iI2ZmZiIgc3Ryb2tlLXdpZHRoPSIxLjUiIHN0cm9rZS1saW5lY2FwPSJyb3VuZCIvPgo8L3N2Zz4K&logoColor=ffffff)](https://zread.ai/YanivHaliwa/media-translation-toolkit)
[![deepwiki](https://img.shields.io/badge/Ask_DeepWiki-_.svg?style=flat&color=00b0aa&labelColor=000000&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB3aWR0aD0iMTYiIGhlaWdodD0iMTYiIHZpZXdCb3g9IjAgMCAxNiAxNiIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPHJlY3Qgd2lkdGg9IjE2IiBoZWlnaHQ9IjE2IiByeD0iMiIgZmlsbD0iI2ZmZiIvPgo8dGV4dCB4PSI4IiB5PSIxMSIgdGV4dC1hbmNob3I9Im1pZGRsZSIgZm9udC1mYW1pbHk9IkFyaWFsLCBIZWx2ZXRpY2EsIHNhbnMtc2VyaWYiIGZvbnQtc2l6ZT0iNyIgZm9udC13ZWlnaHQ9IjcwMCIgZmlsbD0iIzAwMCI+RFc8L3RleHQ+Cjwvc3ZnPgo%3D&logoColor=ffffff)](https://deepwiki.com/YanivHaliwa/media-translation-toolkit/)

 


#version 20.1.26

A comprehensive collection of tools for media downloading, audio transcription, and multilingual translation. This toolkit provides an end-to-end workflow for processing video content, generating subtitles, and translating text across multiple languages.

## 🚀 Features

- **YouTube Video Downloading** - Download videos with automatic filename cleaning
- **Audio Transcription** - Convert speech to text using OpenAI Whisper
- **Multi-language Translation** - Support for 12+ languages with multiple AI backends
- **Subtitle Processing** - Download, match, and translate subtitle files
- **Batch Processing** - Handle multiple files and directories

## 📋 Prerequisites

Before using this toolkit, ensure you have the following installed:

```bash
# Clone the repository
git clone https://github.com/YanivHaliwa/media-translation-toolkit.git
cd media-translation-toolkit

# Make scripts executable
chmod +x *

# Python packages
pip install yt-dlp whisper deep-translator guessit cohere anthropic openai

# System packages (Ubuntu/Debian/Kali)
sudo apt update
sudo apt install ffmpeg python3-pip

# Optional: For enhanced subtitle downloading
sudo apt install subliminal
```

## 🛠️ Tools Overview

### Video & Audio Processing

#### **vidl** - YouTube Video Downloader
Downloads YouTube videos with automatic title extraction and filename cleaning.

**Usage:**
```bash
./vidl <youtube_url>
```

**Example:**
```bash
./vidl "https://www.youtube.com/watch?v=dQw4w9WgXcQ"
# Downloads video as: Never_Gonna_Give_You_Up.mp4
```

#### **vidlsub** - YouTube Video + Subtitles Downloader
Downloads YouTube videos and automatically generates subtitles using Whisper.

**Usage:**
```bash
./vidlsub <youtube_url>
```

**Example:**
```bash
./vidlsub "https://www.youtube.com/watch?v=dQw4w9WgXcQ"
# Downloads video and creates: Never_Gonna_Give_You_Up.srt
```

#### **whis** - Audio Transcription Tool
Transcribes audio files to SRT subtitle format using OpenAI Whisper.

**Usage:**
```bash
./whis [-h] [-m MODEL] [-l LANG] [-o OUTPUT] [-e] audio_file
```

**Options:**
- `-m, --model` - Whisper model: tiny, base, small, medium, large, turbo (default: turbo)
- `-l, --lang` - Language: en, he (default: auto-detect)
- `-o, --output` - Output SRT file path
- `-e, --enhance` - Enhance SRT file with GPT after transcription

**Examples:**
```bash
./whis video.mp4                           # Basic transcription
./whis -m large -l en audio.wav           # Use large model, force English
./whis -e -o subtitles.srt video.mp4     # Enhanced with GPT correction
```

#### **whisi** - Advanced Whisper Transcription
Enhanced Whisper transcription with better performance and additional features.

**Usage:**
```bash
./whisi <audio_file>
```

**Features:**
- Optimized memory usage
- Better GPU utilization
- Advanced error handling
- Multiple model support

### Subtitle & Translation Tools

#### **trsub** - Subtitle Downloader & Translator
Downloads English and Hebrew subtitles for video files, then translates them.

**Usage:**
```bash
./trsub <file_or_directory>
```

**Features:**
- Downloads English subtitles
- Downloads Hebrew subtitles with UTF-8 encoding
- Translates subtitles to Hebrew
- Processes files to match video and subtitle names

**Examples:**
```bash
./trsub video.mkv                    # Process single video
./trsub /path/to/videos/            # Process entire directory
```

#### **trf** - Text & Subtitle Translator
Advanced translation tool with multiple AI backends and format support.

**Usage:**
```bash
python trf -f <file_path> OR -d <directory_path> [options]
```

**Supported Formats:**
- `.srt` (subtitles) - Special formatting preservation
- `.txt` (text files)
- `.md` (markdown files)

**Translation Options:**
- `-l <lang_code>` - Target language (default: he for Hebrew)
- `-gp` - Use ChatGPT for translation
- `-co` - Use Cohere AI for translation
- `-cl` - Use Claude AI for translation

**Supported Languages:**
`he` (Hebrew), `en` (English), `es` (Spanish), `fr` (French), `de` (German), `it` (Italian), `pt` (Portuguese), `ru` (Russian), `zh` (Chinese), `ja` (Japanese), `ko` (Korean), `ar` (Arabic)

**Examples:**
```bash
python trf -f subtitle.srt                    # Translate to Hebrew (default)
python trf -f document.txt -l en              # Translate to English
python trf -f readme.md -l es -gp             # Translate to Spanish with ChatGPT
python trf -d /path/files -l fr -cl           # Translate all files to French with Claude
```

#### **trw** - Quick Word Translator
Fast command-line translator for words and phrases using multiple services.

**Usage:**
```bash
./trw <text_to_translate>
```

**Example:**
```bash
./trw "Hello world"
# Output:
# google translator: שלום עולם
# claude translate: שלום עולם
# chatgpt translate: שלום עולם
```

### File Management Tools

#### **vidsubs** - Video-Subtitle Matcher
Automatically matches video files with their corresponding subtitle files in a directory.

**Usage:**
```bash
./vidsubs <directory_path>
```

**Features:**
- Supports multiple video formats: `.mp4`, `.avi`, `.mkv`, `.ts`
- Intelligent matching using metadata
- Handles TV series episodes and movies
- Processes multiple seasons and episodes

**Example:**
```bash
./vidsubs /path/to/media/folder
# Matches videos with corresponding .srt files
```

## 🔄 Typical Workflows

### Workflow 1: YouTube to Translated Subtitles
```bash
# 1. Download video with auto-generated subtitles
./vidlsub "https://youtube.com/watch?v=VIDEO_ID"

# 2. Translate subtitles to different language
python trf -f Video_Title.srt -l es -cl

# Result: Spanish subtitles generated
```

### Workflow 2: Media Processing & Translation
```bash
# 1. Match videos with existing subtitles
./vidsubs /media/organized

# 2. Download missing subtitles
./trsub /media/organized

# 3. Translate subtitles to multiple languages
python trf -d /media/organized -l es -cl
```

### Workflow 3: Audio Content Processing
```bash
# 1. Transcribe audio file
./whis -m large -e audio_lecture.wav

# 2. Translate transcript to multiple languages
python trf -f audio_lecture.srt -l fr -gp
python trf -f audio_lecture.srt -l de -cl
```

## 🔧 Configuration

### Environment Variables
Some tools require API keys for enhanced functionality:

```bash
# Add to ~/.bashrc or ~/.zshrc
export OPENAI_API_KEY="your_openai_key"
export COHERE_API_KEY="your_cohere_key"
export ANTHROPIC_API_KEY="your_anthropic_key"
```

### Model Downloads
Whisper models are downloaded automatically on first use:
- `tiny` - Fastest, least accurate (~39MB)
- `base` - Good balance (~74MB)
- `small` - Better accuracy (~244MB)
- `medium` - High accuracy (~769MB)
- `large` - Best accuracy (~1550MB)
- `turbo` - Fast and accurate (~809MB) - **Recommended**

## 🚨 Troubleshooting

### Common Issues

**1. Missing Dependencies**
```bash
# Install missing Python packages
pip install yt-dlp whisper deep-translator guessit

# Install system dependencies
sudo apt install ffmpeg
```

**2. Video Download Failures**
```bash
# Update yt-dlp
pip install --upgrade yt-dlp

# Check if URL is valid
yt-dlp --list-formats <url>
```

**3. Whisper Transcription Errors**
```bash
# Check if audio file exists and is valid
ffprobe audio_file.mp3

# Try with smaller model
./whis -m small audio_file.mp3
```

**4. Translation Service Errors**
```bash
# Check API keys are set
echo $OPENAI_API_KEY

# Fall back to Google Translate (no API key needed)
python trf -f file.txt  # Uses Google by default
```

**5. Subtitle Download Issues**
```bash
# Install subliminal for better subtitle support
sudo apt install subliminal

# Check video file format
file video.mkv
```

## 📄 Supported File Formats

### Video Formats
- `.mp4` - Most common, widely supported
- `.mkv` - High quality, supports multiple audio/subtitle tracks
- `.avi` - Legacy format
- `.ts` - Transport stream

### Audio Formats
- `.mp3` - Most common audio format
- `.wav` - Uncompressed audio
- `.m4a` - Apple audio format
- `.flac` - Lossless compression

### Subtitle Formats
- `.srt` - SubRip (most common)
- `.vtt` - WebVTT
- `.ass` - Advanced SubStation Alpha

### Text Formats
- `.txt` - Plain text
- `.md` - Markdown
- `.srt` - Subtitle files

## 📈 Performance Tips

1. **Use appropriate Whisper models:**
   - Use `turbo` for best speed/accuracy balance
   - Use `tiny` for quick processing of large batches
   - Use `large` for critical transcriptions

2. **Batch processing:**
   - Process multiple files in directories when possible
   - Use `trf` with `-d` flag for batch translation

3. **GPU acceleration:**
   - Install CUDA for faster Whisper transcription
   - Use `whisi` for GPU-optimized processing

4. **Storage management:**
   - Organize files before processing using file management tools
   - Keep source files until processing is complete

## 🤝 Contributing

This toolkit is part of Yaniv's cybersecurity and media processing suite. Each tool is designed to work independently or as part of a larger workflow.

## 👨‍💻 Author

Created by [Yaniv Haliwa](https://github.com/YanivHaliwa) for media processing and educational purposes.
