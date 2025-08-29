# AI-Resume-Scanner-Presidio
It is developed using Python and Presidio. It can scan resume and categorize the information accordingly to allow user review a large amount of resumes easily.
Presidio Resume Scanner

Setup Instructions:

1. Make sure Python is installed (https://www.python.org/)
2. Install Tesseract OCR (https://github.com/UB-Mannheim/tesseract/wiki)
   Default path: C:\Program Files\Tesseract-OCR\tesseract.exe
3. Open terminal in this folder and run:

   pip install -r requirements.txt
   python -m spacy download en_core_web_lg

4. Place your resume image as 'resume_sample.jpg' in this folder.
5. Run:

   python scan_resume_pii.py

You can also run test_presidio.py for a text-only PII test.
