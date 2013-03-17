scan
====

This app provides a simple GUI for acquiring images from a scanner on Linux.  
It allows selecting the scan dimensions, resolution and a filename to write 
to.  To simplify batch scanning, a five-digit number is appended to the 
filename, and incremented to the next available number.

The scanner app uses WxPython.


Also, jpg2pdf is a shell script, which uses ImageMagick's 'convert' to take a 
set of JPG files provided on the command line, and convert them to a single 
PDF, one image per page.  I use this script to simplify scanning multi-page 
documents to PDF, but it assumes letter-size paper scanned at 150 dpi.

