# PDF Exhibit Watermark Tool

Automatically watermark exhibit numbers and descriptions onto every page of PDF documents using a simple Google Colab notebook.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/saintjcp/pdf-exhibit-watermark-tool/blob/main/PDF_Exhibit_Watermark_Tool.ipynb)

## Overview

This tool automatically stamps exhibit numbers and descriptions onto every page of uploaded PDF files.  
The exhibit number and description are read directly from the file name.

Example file name format:

EXHIBIT 11.3 - Operations Located in Low Cost Energy Regions.pdf

The notebook then applies a diagonal watermark to every page.

## How It Works

1. Open the notebook in Google Colab.
2. Upload one or more PDF exhibits.
3. The notebook automatically reads the exhibit number and description from the file name.
4. Watermarked PDFs are generated and saved to a download folder.

## File Naming Format

Name your files like this:

EXHIBIT NUMBER - DESCRIPTION.pdf

Example:

EXHIBIT 5.1 - Investor Presentation.pdf

## License

MIT License
