
# Tesseract OCR Text Extraction

## About
This project demonstrates how to use **Tesseract OCR** (Optical Character Recognition) to extract text from an image file. The example processes a simple image containing the text **"The Quick Brown Fox Jumps Over The Lazy Dog"** and outputs the extracted text in two formats:

- **Character-by-character sequence**
- **Word-by-word sequence**

## Folder Structure

```
Tesseract-OCR-Project/
├── Tesseract OCR.ipynb       # Jupyter notebook containing the OCR implementation
├── text2.jpeg                # Sample image file for text extraction
├── Outputcharacters.txt      # Output file with characters separated by newlines
└── Outputword.txt            # Output file with words separated by newlines
```

## Tech Stack

- **Python** - Primary programming language
- **Tesseract OCR** - Open-source OCR engine
- **pytesseract** - Python wrapper for Tesseract
- **OpenCV** - For image processing capabilities
- **Pillow (PIL)** - Python Imaging Library for image handling

## How to Use

### Prerequisites

- Install Tesseract OCR on your system:

```bash
sudo apt-get install tesseract-ocr
```

- Install Python dependencies:

```bash
pip install pytesseract opencv-python pillow
```

### Running the Project

1. Open the Jupyter notebook `Tesseract OCR.ipynb`
2. Execute the cells in sequence:
   - First cell installs Tesseract OCR
   - Second cell installs Python dependencies
   - Subsequent cells perform the text extraction

The notebook will:
- Extract text from `text2.jpeg`
- Create `Outputcharacters.txt` with each character on a new line
- Create `Outputword.txt` with each word on a new line

### Customization

- Replace `text2.jpeg` with your own image file
- Modify the config parameters (`--psm 6 --oem 3`) for different OCR modes
- Adjust the output file names and formats as needed

> **Note:** The project is configured to work in **Google Colab** by default but can be adapted for local execution by adjusting the Tesseract path if needed.

---

### **Author**  
**Izaan Ibrahim Sayed**  
Email: izaanahmad37@gmail.com  
GitHub: [github.com/izaanahmad37](https://github.com/izaanibrahim37) 
