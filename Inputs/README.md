# MOM Generator 🤖

AI-powered Minutes of Meeting (MOM) generator that extracts text from images, PDFs, and DOCX files to create standardized meeting minutes.

WebLink: 

## 🌟 Features

- **Multi-format Text Extraction**: Extract text from Images, PDFs, and DOCX files
- **Advanced OCR**: Compare Tesseract and Google AI OCR methods
- **AI-Powered MOM Generation**: Create standardized meeting minutes using Google Gemini AI
- **Text Summarization**: Generate concise summaries of meeting notes
- **Multi-file Processing**: Combine and process multiple documents
- **Web Interface**: User-friendly Streamlit web application
- **File Download**: Download generated MOMs and summaries

## 🚀 Quick Start

### Prerequisites
- Python 3.10+
- Google AI API key (for OCR and MOM generation)

## 📁 Project Structure
MOM-generator/
├── webapp.py                 # Streamlit web application

├── Loadig text.ipynb         # Jupyter notebook for development

├── imageextractor.py         # Image text extraction module

├── pdfextractor.py           # PDF text extraction module

├── docxextractor.py          # DOCX text extraction module

├── requirements.txt          # Python dependencies

├── README.md                 # Project documentation

├── .gitignore                # Git ignore file

└── outputs/                  # Generated files directory


## 🔧 Configuration
Environment Variables
- GOOGLE_API_KEY: Your Google AI API key for text processing and MOM generation
Supported File Formats
- Images: PNG, JPG, JPEG
- Documents: PDF, DOCX
- OCR Methods: Tesseract OCR, Google AI Vision

## 🎯 Features in Detail
Text Extraction
- Images: Uses OpenCV preprocessing + Google AI for accurate OCR
- PDFs: Extracts text using pypdf library
- DOCX: Parses Word documents using python-docx
MOM Generation
Creates standardized minutes of meeting with:
- Meeting title and agenda
- Attendees and location
- Key points discussed
- Decisions made
- Actionable items
- Deadlines and next meetings
- Summary

---
