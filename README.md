# IIIF_Text_Analysis

Welcome to my IIIF for Text Analysis GitHub repository. This repository includes a python notebook that contains all of the code necessary to transform JPEGs from IIIF manifests into machine readable text documents that can undergo text analysis digital humanities methods.

This notebook will show you how to do text analysis on digitized archival materials available in UCLA Library Digital Collections. The workflow provides a good introduction to using python in the command line.

Text analysis is a computational research methodology that allows a researcher to analyze linguistic trends in a large corpus of text by rendering the text machine readable. When text is machine readable, this means a computer can point to all instances of a given word. This allows researchers to study how often a word appears within a given set of texts, how word usage change over time, when a word first appears, words that tend to appear in connection with each other, and so on.

Libraries are increasing digitizing their archival collections, but it takes some work to be able to do text analysis on those digital collections if those libraries only make images available for close reading (like UCLA Digital Collections). This colab notebook shows you how to prepare images from online digital collections for text analysis.

**Steps used in this workflow:**

1. Mass-download JPEG images from IIIF-based digital libraries (PYTHON)
2. Mass-convert JPEGs to PDFs (PYTHON)
3. Mass-render PDFs as text-searchable (OCR the PDFs) (BASH)
4. Mass-convert PDFs to .txt files (BASH)

**Skill development:** 

Increase comfort using the command line (e.g., download files from the internet, manipulate files on your computer)

**Future Goals:**

1. Make the workflow more automatable/iterative (e.g., use query strings to automate the processing of multiple manifests in a row without having to copy-paste manifests
2. Clean up file naming aspects of the workflow to reflect best practices in data management
