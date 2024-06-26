# Document-Summarizer

```markdown
 Document Summarization App

## Overview
This Streamlit-based application uses a language model to summarize PDF documents. It leverages the LaMini-Flan-T5-248M model for efficient text summarization.

## Features
- PDF upload functionality
- Automatic text extraction from PDFs
- AI-powered document summarization
- Side-by-side display of original PDF and generated summary

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/document-summarization-app.git
   cd document-summarization-app
   ```

2. Create a virtual environment:
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

## Usage

1. Run the Streamlit app:
   ```
   streamlit run app.py
   ```

2. Open your web browser and navigate to the provided local URL (usually http://localhost:8501).

3. Upload a PDF file using the file uploader.

4. Click the "Summarize" button to generate a summary.

## Technology Stack
- Streamlit
- LangChain
- Hugging Face Transformers
- PyTorch
- PyPDF

## Model
This app uses the LaMini-Flan-T5-248M model for summarization. The model is automatically downloaded when you run the application for the first time.
