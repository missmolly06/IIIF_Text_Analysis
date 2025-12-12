# IIIF_Text_Analysis

Welcome to my IIIF for Text Analysis GitHub repository. This repository is a work in progress. 

Text analysis is a computational research methodology that allows a researcher to analyze linguistic trends in a large corpus of text by rendering the text machine readable. When text is machine readable, this means a computer can point to all instances of a given word. This allows researchers to study how often a word appears within a given set of texts, how word usage change over time, when a word first appears, words that tend to appear in connection with each other, and so on.

Libraries are increasing digitizing their archival collections, but it  takes some work to be able to do text analysis on those digital collections if those libraries only make images available for close reading (like UCLA Digital Collections). 

Currently, this GitHub repository includes a python notebook that contains all of the code necessary to mass-download images from digital libraries and transform them into machine readable text documents that can undergo text analysis digital humanities methods. This notebook will show you how to do text analysis on digitized archival materials available in UCLA Library Digital Collections,  providing a good introduction to using python in the command line.

**Steps used in this workflow:**

1. Download JPEG images from IIIF-based digital libraries (PYTHON)
2. Convert JPEGs to PDFs (PYTHON)
3. Render PDFs as text-searchable (OCR the PDFs) (BASH)
4. Convert PDFs to .txt files (BASH)

**Skill development:** 

1. Increase comfort using (and differentiating between) python and bash programming commands (e.g., download files from the internet, manipulate files on your computer)
2. Learn how to package command line code in multiple languages into a jupyter notebook-based tutorial

**Future Goals:**

1. Make the workflow more automatable/iterative (e.g., use query strings to automate the processing of multiple manifests in a row without having to copy-paste manifests
2. Clean up file naming aspects of the workflow to reflect best practices in data management
3. There are some areas where I resorted to Chat-GPT to help me create code because the more simple code I learned from other tutorials did not work. I'm interested in contintuing to troubleshoot that simpler code to get it to work.
