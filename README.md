# **Text Extraction Engine**

---
### **Contents**
- [Introduction](#Introduction)
- [Run Locally](#Run-Locally)
- [Features](#Features)
- [Tech Stacks & Libraries](#Tech-Stacks-&-Libraries)
- [Model API's](#Model-API's)
- [References](#References)

---
### **Introduction**
File Analysis involves examining the data within a file and extracting meaningful information. This web application is designed to provide an interface that extracts text from an image, searches for a specific phrase, and returns its position within the image. A File Analyzer can automate the process of extracting information from large volumes of unstructured text documents, saving time and reducing manual labor costs. It minimizes the risk of errors and inconsistencies that often arise during manual information extraction. Additionally, it offers a scalable solution for organizations that need to process a substantial number of documents efficiently.

Report
---
### **Run Locally**
Clone the repo in virtual environment and open the website using the following commands:
```bash
git clone https://github.com/tanu0009/FileAnalyzer.git
cd FileAnalyzer/client
npm install
npm run dev
```
---

### **Features**
- Extracting content from images or PDF files  
- Identifying and retrieving email addresses and phone numbers  
- Generating concise summaries of extracted content  
- Analyzing the sentiment of text and categorizing it as positive or negative  
- Locating and marking the input word or phrase within the extracted text and input image using bounding boxes wherever it appears  
- Enabling voice input to enhance the search functionality  
- Converting extracted text into audio for speech playback  
- Allowing users to export processed information into a downloadable PDF document  

---

### **Tech Stacks & Libraries**
- ReactJS
- Hyper Text Markup Language (HTML)
- Cascading Style Sheets (CSS)
- Javascript
- Tesseract.js
- React-pdf, React-speech, React-speech-kit

--- 
### **Model API's** chena
- [BART model](https://huggingface.co/facebook/bart-large-cnn)
- [DistilBERT base uncased finetuned SST-2](https://huggingface.co/distilbert-base-uncased-finetuned-sst-2-english)

---
### **References**
- https://tesseract.projectnaptha.com
