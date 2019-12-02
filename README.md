[![Build Status](https://travis-ci.com/tsrsilva/ocr-script.svg?branch=master)](https://travis-ci.com/tsrsilva/ocr-script)
[![codecov.io](https://codecov.io/github/tsrsilva/ocr-script/coverage.svg?branch=master)](https://codecov.io/github/tsrsilva/ocr-script?branch=master)
![MIT license](https://img.shields.io/github/license/tsrsilva/ocr-script)

# OCR script
A shell script for optical character recognition (OCR) of PDF files.


## Table of Contents
  * [Dependencies](#dependencies)
  * [Configuration](#configuration)
  * [Running](#running)
    * [Windows](#run_windows)
    * [Unix](#run_unix)
  * [Issues](#issues)

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

<a name="running"></a>
## Running

<a name="run_windows"></a>
### Windows

To run the ocr script in Windows you will need to install the Windows Subsystem for Linux (WSL).
To do that, you will need to go to Settings > Update & Security > For Developers tab and
check the **Developer Mode** button. At the same tab, search for **Windows Features** and
choose **Turn Windows features on or off**.

Scroll to find WSL, check the box, and then install it. Once done, you will have to reboot your
system to finish installing the requested changes. After that, the *bash* command will be available
in the Command Prompt and PowerShell.

To execute the script, open the **Command Prompt** or **PowerShell** and navigate to
the folder where the script file is available. Then, type

```
bash ocr.sh
```

and hit enter.

<a name="run_unix"></a>
### Unix

To run the ocr script in Unix-based operating systems (*i.e.* macOS and Linux) you just need to
set execute permissions to the file and run it using **bash**.

To set execute permissions type

```
chmod +x ocr-script.sh
```

and run it using

```
./ocr-script.sh
```

or

```
sh ocr-script.sh
```

or

```
bash ocr-script.sh
```

<a name="issues"></a>
### Issues

The most straightforwad mechanism for asking questions, reporting problems, or requesting additions to the script is the [issue tracker](https://github.com/tsrsilva/ocr-script/issues).
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTIxMjk5NDc4MzhdfQ==
-->
