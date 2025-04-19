# Generative AI Text Summarization Tool

This tool allows you to upload text, PDF, and Word files and generate summaries using the OpenAI API.

## Requirements

-   Python 3.7+
-   Streamlit
-   OpenAI
-   PyPDF2
-   python-docx
-   reportlab

## Installation

1.  Clone the repository:

    ```bash
    git clone <repository_url>
    ```

2.  Install the dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3.  Set the OpenAI API key:

    Replace `"YOUR_API_KEY"` with your actual OpenAI API key in the `streamlit_app.py` file.

## Usage

1.  Run the Streamlit application:

    ```bash
    streamlit run streamlit_app.py
    ```

2.  Open the application in your browser and upload a document.

3.  View the generated summary and download it in text, PDF, or Word format.
