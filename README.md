# feature_extraction_paddleocr
# Feature Extraction from Images Using PaddleOCR
This project leverages PaddleOCR for Optical Character Recognition (OCR) to extract text from images, followed by text cleaning and the application of regular expressions (regex) to retrieve specific features such as weight, height, volume, depth, and width.

# Problem Statement
Many image-based datasets contain crucial information embedded in text, such as product dimensions or specifications. This project automates the extraction of such information, streamlining the process of gathering structured data from unstructured sources.

#Solution
OCR with PaddleOCR: Used to extract textual data from images.
Text Cleaning: The extracted text is cleaned and converted to lowercase to ensure uniformity.
Feature Extraction with Regex: Regular expressions are applied to detect and extract specific features such as:
Weight
Height
Volume
Depth
Width
Workflow
OCR Extraction:
Images are processed through PaddleOCR to extract any text embedded in them.
Text Cleaning:
The extracted text is converted to lowercase and cleaned by removing unnecessary characters.
Regex for Feature Extraction:
Custom regular expressions are applied to extract specific features like weight, height, volume, depth, and width from the cleaned text.
Tools & Libraries
PaddleOCR: For extracting text from images using Optical Character Recognition.
Regex (Regular Expressions): To identify and extract specific features from the cleaned text.
Python Libraries: General text processing tools and image handling libraries like OpenCV.
