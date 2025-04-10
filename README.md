# 🖼️ Image to Text Converter using Flask
This project is a simple web application that allows users to upload an image and extract text from it using Python's OCR capabilities (like pytesseract). It uses Flask for the backend and HTML for the frontend.

## 📁 Files

- `app.py` - Python Flask backend
- `templates/index.html` - Frontend HTML page for uploading images

## ⚙️ How It Works

1. User uploads an image through the webpage.
2. The Flask server receives the image.
3. Python extracts the text using OCR.
4. The result is displayed on the page.

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Mahaashri/image-to-text-converter.git
   cd image-to-text-converter

2. Install required packages:
   pip install flask pytesseract Pillow

3. Run the app:
   python app.py

4.Open your browser and go to:
http://127.0.0.1:5000/
