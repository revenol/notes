# Latex

## Graphics

- [Tsingke's blog](http://www.cnblogs.com/tsingke/p/6649800.html): a collection of Graphics in Latex

## EPS
- Gsviewer: Only [Gsviewer 5.0](http://pages.cs.wisc.edu/~ghost/gsview/get50.htm) (or before) allows editing eps's bounding box:
  1. 'Options' -> 'Show Bounding Box'
  1. 'File' -> 'PS to EPS' -> 'Automatically calculate Bounding Box'. It will generate a new EPS file after croping bounding box.

- A register code for Gsviewer 5.0:
  1. 'Name': any name
  1. 'code': 55555 - 24868

- Generate EPS from Acrobat Pro (recommned):
  1. Save the figure as PDF file.
    - Generated from MATLAB:
      1. Save the figure as PDF File.
      1. Open the PDF file, print as a PDF file. The print engine will replace the MATLAB's Helvetia font with TimesNewRome font, and embed all fonts.
    - Generated from Visio:
      1. Print as a PDF file.
  1. Open the PDF file with Acrobat Pro:
    1. Edit the file and crop it into the exact size.
    1. Export as an EPS file.
