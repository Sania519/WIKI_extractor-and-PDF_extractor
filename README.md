# WIKI_extractor-and-PDF_extractor

WIKI_Extractor:

Libraries used are:
wikipedia, json, request and BeautifulSoup

Wikipedia is a module(API) to scrap the data from the Wikipedia pages. This module allows us to get and parse the information from Wikipedia. In simple words, we can say that it is worked as a little scrapper and can scrap only a limited amount of data.

I have used the pre-defined methods from the module to search information on a word. The search() method returns the name of titles related to the word searched. 
The page() method returns its page.
I have used request and BeautifulSoup to scrape content from it. The urls and the content(a paragraph, here) are stored as a json file.

PDF_Extractor:

Libraries used are:
Pandas, pdf2image (convert_from_path), pytesseract, pdf2image, os, PyPDF2

Pandas is used to work on the csv file containing the links provided to all the links of the pdfs.
PyPDF2 is used to extract the pdf from the urls, wget is also used to download the pdfs.
Pytesseract-ocr-hin is used to extract hindi text from the pdfs downloaded.
Here, first the pdfs are converted in to images and then the ocr model is used to extract text from the images.


