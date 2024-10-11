# Google-Gemini-Pro-LLM-Multiple-Pdf-Documents-Reader

## Overview

This project provides a web application that utilizes the Google Gemini Pro LLM (Large Language Model) to read and extract information from multiple PDF documents. Users can upload multiple PDFs at once, and the application will process them to retrieve relevant content, summaries, and insights.

## Features

Upload multiple PDF documents simultaneously

Automatic extraction of text and key information

Summarization of document content

Search functionality across uploaded documents

User-friendly web interface

## Technologies Used

Backend: Streamlit

Frontend: HTML

LLM: Google Gemini Pro

PDF Processing: PyMuPDF or pdfminer

Deployment: Docker (optional)

## Requirements

Python 3.x

Streamlit or Flask or FastAPI

requests (for API calls to Google Gemini)

PyMuPDF or pdfminer (for PDF text extraction)

Other dependencies (listed in requirements.txt)

## Usage

Navigate to the home page of the application.

Upload multiple PDF documents using the provided interface.

Click the "Process" button to extract text and generate summaries.

Use the search functionality to find specific information across all uploaded documents.

## Deployment

To deploy the app, consider using platforms like Heroku, AWS, or Google Cloud. Ensure you have the necessary environment variables and configurations set up.
