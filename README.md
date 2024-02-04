# Text Extraction from Images

This repository contains code for extracting text from images using Python. The script utilizes Tesseract OCR and PIL (Python Imaging Library) for text extraction from images.

## Installation

Before running the script, you need to install the necessary dependencies. Execute the following commands:

```bash
!sudo apt install tesseract-ocr
!pip install pytesseract
!pip install XlsxWriter
```

## Usage

1. Clone the repository to your local machine or directly use it in Google Colab.
2. Run the provided notebook `Text_Extraction_copy.ipynb`.
3. Upload images containing text into the `images` folder created by the notebook.
4. Execute the notebook cells to extract text from the images and store it in an Excel file (`out.xlsx`).

## Requirements

- Python 3
- Tesseract OCR
- pytesseract
- XlsxWriter
- PIL (Python Imaging Library)

## How it works

The notebook first installs the required packages (`pytesseract` and `XlsxWriter`). It then imports necessary libraries and creates an `images` folder if it doesn't exist. Users need to upload images to this folder.

The script iterates through the images in the `images` folder, extracts text using Tesseract OCR, and stores the extracted information in an Excel file (`out.xlsx`).

## Contributors

- [Venkata Sai](https://github.com/venkatasai7)

Feel free to contribute to this project by opening issues or submitting pull requests. Your feedback and contributions are highly appreciated!
