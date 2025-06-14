# Yaniv Project: Media Translation Toolkit

#version 14.6.25

## Project Overview
This is a comprehensive media processing and translation toolkit that combines video downloading, audio transcription, subtitle processing, and multilingual translation capabilities. The project was split from Linux-Stuff repository to create a focused toolkit for media and translation workflows.

## Project Structure
```
media-translation-toolkit/
├── README.md (comprehensive documentation)
├── .gitignore (configured for media files)
├── movef (file organization tool)
├── trf (AI-powered translator - Python)
├── trsub (subtitle downloader & translator - Bash)
├── trw (quick word translator - Python)
├── vidl (YouTube video downloader - Bash)
├── vidlsub (video downloader + transcription - Bash)
├── vidsubs (video-subtitle matcher - Python)
├── whis (Whisper transcription with GPT enhancement - Python)
└── whisi (advanced Whisper transcription - Python)
```

## Tools Functionality

### Video & Audio Processing
1. **vidl** - Downloads YouTube videos with automatic filename cleaning
2. **vidlsub** - Downloads YouTube videos + generates subtitles using Whisper
3. **whis** - Transcribes audio to SRT format with multiple Whisper models + GPT enhancement
4. **whisi** - Advanced Whisper transcription with GPU optimization

### Translation & Text Processing
1. **trf** - Multi-format file translator (SRT, TXT, MD) with multiple AI backends
2. **trw** - Quick command-line translator using Google/Claude/ChatGPT
3. **trsub** - Downloads and translates subtitles for video files

### File Management
1. **movef** - Organizes files from subdirectories with conflict resolution
2. **vidsubs** - Matches video files with corresponding subtitle files

## What Yaniv Asked For

### ✅ COMPLETED Tasks:
- [x] Create comprehensive README with accurate tool documentation
- [x] Use --help output and script inspection for accurate usage examples
- [x] Document all command-line options and parameters
- [x] Include installation prerequisites and dependencies
- [x] Add workflow examples showing typical usage patterns
- [x] Include troubleshooting section for common issues
- [x] Document supported file formats
- [x] Add configuration section for API keys
- [x] Include performance tips and optimization advice
- [x] Add proper version header (14.6.25)
- [x] Create this project tracking file

### Tool Documentation Quality:
- **vidl**: Complete with usage examples
- **vidlsub**: Complete with workflow description
- **whis**: Complete with all CLI options documented from --help
- **whisi**: Complete with feature description
- **trf**: Complete with all translation options and language codes
- **trw**: Complete with output examples
- **trsub**: Complete with feature breakdown from script analysis
- **vidsubs**: Complete with metadata matching description
- **movef**: Complete with conflict resolution details

### Key Features Documented:
- Multiple AI translation backends (Google, ChatGPT, Claude, Cohere)
- 12+ language support with language codes
- Whisper model options (tiny to turbo)
- GPU acceleration capabilities
- Batch processing workflows
- API key configuration
- File format support
- Performance optimization tips

## Repository Status
- ✅ Git initialized and configured
- ✅ Remote set to GitHub (YanivHaliwa/media-translation-toolkit)
- ✅ .gitignore properly configured for media files
- ✅ All files committed and pushed
- ✅ README comprehensive and accurate

## Dependencies Documented
- System: ffmpeg, python3, pip
- Python packages: yt-dlp, whisper, deep-translator, guessit, cohere, anthropic, openai
- Optional: subliminal for enhanced subtitle support
- Environment variables: OPENAI_API_KEY, COHERE_API_KEY, ANTHROPIC_API_KEY

## Workflows Documented
1. YouTube to translated subtitles pipeline
2. Media folder organization workflow  
3. Audio content processing and translation
4. Batch processing examples

This project is now complete with professional documentation ready for GitHub and production use.
