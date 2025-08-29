# PDF to Text Extractor

A simple and straightforward Python program to extract text from PDF files and save the output to a `.txt` file.

## Features

-   Extracts text from single or multiple PDF files.
-   Saves the extracted text into clean, separate `.txt` files.
-   Simple command-line interface.

## Installation

1.  **Clone this repository:**
    ```bash
    git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git
    cd your-repository-name
    ```

2.  **Install the required dependency (PyPDF2):**
    ```bash
    pip install PyPDF2
    ```

## Usage

1.  Place the PDF file(s) you want to process in the `input_pdfs/` folder (create it if it doesn't exist).
2.  Run the script:
    ```bash
    python pdf_to_text.py
    ```
3.  The extracted text files will be saved in the `output_texts/` folder.
