# ocr_web_app
# OCR and Document Search Web Application

## Overview
This web application performs Optical Character Recognition (OCR) on uploaded images containing text in both Hindi and English. It also allows users to search for keywords within the extracted text.

## Features
- Upload images (JPEG, PNG) for OCR processing.
- Extracted text displayed on the same page.
- Basic keyword search functionality to highlight matching sections.

## Requirements
- Python 3.6 or higher
- Tesseract OCR installed on your system
- Required Python packages:
  - `torch`
  - `transformers`
  - `gradio`
  - `pytesseract`
  - `Pillow`
  - `numpy`

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/ocr-document-search-app.git
   cd ocr-document-search-app
   
