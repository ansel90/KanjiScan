# KanjiScan

[English](README.MD) | [Русский](README.RU.MD)

Scan Japanese images, export to Anki cards

## Features

- **AI-powered OCR**: Extract Japanese text from images using GPT-4 Vision
- **Grammar analysis**: Breaks down words, constructions, and expressions
- **Personal dictionary**: Build and manage your Japanese vocabulary collection
- **Anki export**: Download results in CSV format compatible with Anki flashcards
- **Russian interface**: Currently supports Russian language only
- **Infinite scroll**: Browse large dictionaries efficiently
- **Responsive design**: Works on desktop and mobile devices

## Quick Start

1. Open [https://ansel90.github.io/KanjiScan](https://ansel90.github.io/KanjiScan)
2. Go to Settings and enter your OpenAI API key
3. Upload a Japanese image on the Upload page
4. Click "Analyze" to extract and process text
5. Save results to dictionary or download as CSV

## Supported Models

GPT-4o (recommended for best accuracy) or any OpenAI model with vision capabilities.



## Analysis Output

Each analyzed element includes the Japanese word or construction, Russian translation with grammatical explanation, and contextual usage example.



## Requirements

OpenAI API key with access to GPT-4 Vision models and a modern web browser.

## CSV Export Format

The exported CSV contains three columns compatible with Anki: Japanese word/construction, Russian translation/explanation, and contextual example.

## Local Development

```bash
git clone https://github.com/ansel90/KanjiScan
cd KanjiScan
# Open index.html in browser or serve with local server
```



## Support

If you encounter issues, check the browser console for errors, verify your API key has vision model access, and ensure image quality is sufficient for text recognition. You can also create an issue in the GitHub repository.

## About the Project

This application was created with AI assistance (Claude) for personal Japanese learning needs. The entire codebase was generated through AI collaboration and may not reflect traditional software development practices.

Shared publicly in case it might be useful to others in the Japanese learning community.

**Please note**: This is an AI-generated project created for specific personal use cases. While we welcome constructive feedback and bug reports, the code quality and architecture are products of AI generation rather than manual development. For those seeking different coding standards or architectural approaches, we encourage forking the project or building your own solution.

## License

GPL-3.0 License
