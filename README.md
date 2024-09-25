PDF Utility Tool
This Python-based PDF Utility Tool offers an easy-to-use graphical interface for managing and optimizing PDF files. It combines various functionalities such as scanning documents, merging front and back images, and reducing PDF file size using Ghostscript.

Features:
Front/Back Scanning: Scan and combine front and back pages of a document into a single PDF.
PDF Compression: Automatically reduce the size of a PDF file using Ghostscript. If Ghostscript is not installed, the program will download and install it for you.
User-Friendly Interface: Simple and intuitive interface for selecting files, saving outputs, and managing scans.
Admin Privileges: The program requests admin privileges automatically if required for installing Ghostscript or handling certain system tasks.
Requirements:
Python 3.x
Required libraries: win32com.client, opencv-python, requests, fpdf, PyPDF2, and others.
How to Use:
Clone the Repository: Clone this repository to your local machine.
Install Dependencies: Install the required libraries using pip (pip install -r requirements.txt).
Run the Program: Run the Python script to launch the utility interface.
Ghostscript Installation: If Ghostscript is not installed, the program will automatically download and install it.
License:
This project is licensed under the MIT License.
