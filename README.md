# Textual_PDF_to_Audio_using_python
A Python library for Text to Speech. It has many functions which will help the machine to communicate with us. It will help the machine to speak to us.

### Approach:

1. Import the PyPDF2 and pyttx3 modules.
2. Open the PDF file.
3. Use PdfFileReader() to read the PDF. We just have to give the path of the PDF as the argument.
4. Use the getPage() method to select the page to be read.
5. Extract the text from the page using extractText().
6. Instantiate a pyttx3 object.
7. Use the say() and runwait() methods to speak out the text.
