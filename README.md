## 🚀 Project Overview
This tool converts PDF files into images and applies Tesseract OCR to detect and extract text from each page. It is especially useful for scanned documents or image-based PDFs that do not contain machine-readable text.

The extracted text is cleaned, structured, and made ready for downstream tasks such as text analysis, classification, or storage.

## ⚙️ Tech Stack
Tesseract OCR – Core engine for optical character recognition

PDF to Image Conversion – Converts PDF pages to high-resolution images using libraries like pdf2image or PyMuPDF

OpenCV / PIL – For image preprocessing (optional enhancement)

Python – Core scripting language for the pipeline

## 🔧 Features
Supports multi-page PDF processing

Handles scanned/image-only PDFs

Extracts and outputs plain text

Optional: image preprocessing for improved OCR accuracy (e.g., grayscale, thresholding)

