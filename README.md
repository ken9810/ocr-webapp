# OCR Webapp

A simple Flask web application for uploading receipt images and extracting text using Tesseract OCR.

## Features
- Upload receipt images via web interface
- Extract text using pytesseract

## Development Container
This project includes a dev container setup using Ubuntu and Python 3.13. Tesseract OCR is installed in the container.

## Usage
1. Open in VS Code and reopen in container.
2. Install dependencies (auto-installed in container).
3. Run `python3 app.py` inside the container.
4. Access the webapp at `http://localhost:5000`.

## Requirements
- Python 3.13+
- Flask
- Pillow
- pytesseract
- Tesseract OCR

## License
MIT
