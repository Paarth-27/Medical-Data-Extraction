# Medical-Data-Extraction
 OCR-based system for automating medical data extraction
### 1. Introduction
This project is designed for efficient extraction and automatic classification of valuable data from medical documents. It leverages several key libraries, including Pytesseract (powered by Google OCR), OpenCV, Regex, PDF2Image, and Pytest, to streamline the extraction process. Initially, PDF2Image converts PDF documents to images, followed by image enhancement using OpenCV’s Adaptive Thresholding technique. Pytesseract and Regex are then used to retrieve relevant information such as patient details, medications, and other essentials. This solution significantly reduces the processing time, cutting it from 15 minutes down to about 2 minutes.

### 2. Major Libraries and Tools
- **PDF2Image**: Converts medical PDF documents to images for further processing.
- **OpenCV**: Processes and enhances the images using adaptive thresholding to improve data extraction accuracy.
- **Pytesseract**: Employs Google OCR to recognize and extract text from the processed images.
- **Regex**: Utilized for precise extraction of required data fields from the recognized text.
- **Pytest**: Ensures comprehensive testing and quality control for the code.

### 3. Project Tasks
- Gather and prepare the dataset.
- Analyze data to identify key information.
- Convert PDFs to images using PDF2Image.
- Clean and enhance images using OpenCV’s adaptive thresholding.
- Extract text from cleaned images using Pytesseract (OCR).
- Use Regex to retrieve specific information from the extracted text.
- Validate code and project performance using Pytest.

### 4. Future Goals
Further improvements could include integrating advanced Computer Vision techniques like Region of Interest (ROI) to boost data extraction accuracy. Additional Regex rules may also be applied to capture more fields, providing deeper insights and reducing time consumption even further.
