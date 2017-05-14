# IMAGE-TO-CODE



Image-to-code is a python based OCR tool specifically made to capture an image with a code-snippet, and instantly get in in text form onto a text editor for the user.

It uses the pytesseract wrapper for the tesseract-OCR and pyGtk for GUI.


### Usage

Simply run the gui1.py file using the terminal.

```sh
$ python gui1.py
```
This will open up a simple text editor.

Then, follow these steps:
  - Click the choose file button, and choose an image file with the code-snippet in it
  - Click the scan button
  - The code from the image comes into the text editor (the language of the code is identified and is highlighted accordingly)

(You may have to edit the scanned code as the OCR is not perfect, and can result in abnormal scans)

### Future features

  - Add support for other popular languages
  - Drag and drop images
  - Train the OCR for better results
  - Enhance the text editor


### Tech

Image-to-code uses a number of open source projects to work properly:

* [Tesseract-OCR](https://github.com/tesseract-ocr/tesseract) - OCR library
* [Pytesseract](https://pypi.python.org/pypi/pytesseract/0.1) - python wrapper for Tesseract
* [PyGTK](http://www.pygtk.org/) - GTK for python
* [Pygments](http://pygments.org/) - Syntax highlighter
* [Pillow](https://pypi.python.org/pypi/Pillow/) - Python imaging library

Others: 
* [Matplotlib](https://matplotlib.org/)
* [NumPy](http://www.numpy.org/)
* [SciPy](https://www.scipy.org/)

