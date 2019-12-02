[![Build Status](https://travis-ci.com/tsrsilva/ocr-script.svg?branch=master)](https://travis-ci.com/tsrsilva/ocr-script)

# OCR script
A shell script for optical character recognition (OCR) of PDF files.


## Table of Contents
  * [Dependencies](#dependencies)
  * [Configuration](#configuration)
  * Issues

<a name="dependencies"></a>
## Dependencies

To properly run this script, you will need to install three dependencies: 

  * [Xpdf's pdftotext](https://www.xpdfreader.com/pdftotext-man.html)
  * [Tesseract OCR](https://github.com/tesseract-ocr/)
  * [ImageMagick](https://imagemagick.org/)

<a name="configuration"></a>
## Configuration

Before starting the character recognition process, you will need to determine the
input and output directories in ocr.sh. Open the file with your favorite text
editor and call the input path (*i.e.* the directory that your files that are
going to be OCRed are located) and output path (*i.e.* the directory that will
receive your OCRed files) respectively.

