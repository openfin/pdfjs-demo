# pdfjs-demo
Demo of integration of the PDFJS project into OpenFin for inline PDF viewing

Following setup curtesy of https://github.com/mozilla/pdf.js/wiki/Setup-pdf.js-in-a-website is used:

1. Download https://github.com/mozilla/pdf.js/archive/gh-pages.zip.

2. Extract the ZIP file (a directory called "pdf.js-gh-pages" will be created).

3. Copy the following directories to the website:

* pdf.js-gh-pages/build/
* pdf.js-gh-pages/web/
* The web/ directory contains a 1 MB PDF file called "compressed.tracemonkey-pldi-09.pdf". This file is only used as an example for the demo and can safely be removed.

- `npm install`
- `npm start`
- `openfin -l app.json`

See https://github.com/mozilla/pdf.js/ for details of the PDFJS project.
