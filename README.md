# PDFJS Example

## Overview
The following repo is an example of how to leverage the [PDFJS project](https://github.com/mozilla/pdf.js/) (opensource) for inline PDF viewing in your OpenFin application.

## Guidelines
Following setup curtesy of https://github.com/mozilla/pdf.js/wiki/Setup-pdf.js-in-a-website:

1. Download [gh-pages](https://github.com/mozilla/pdf.js/archive/gh-pages.zip)
2. Extract the ZIP file (a directory called "pdf.js-gh-pages" will be created).
3. Copy the following directories to the website:

* pdf.js-gh-pages/build/
* pdf.js-gh-pages/web/
* The web/ directory contains a 1 MB PDF file called "compressed.tracemonkey-pldi-09.pdf". This file is only used as an example for the demo and can safely be removed.

## Launch
### Run locally
- `npm install`
- `npm start`
- `openfin -l app.json`

## More Info
See [PDFJS Project](https://github.com/mozilla/pdf.js/) for more details.

## Disclaimers
* This is a starter example and intended to demonstrate to app providers a sample of how to approach an implementation. There are potentially other ways to approach it and alternatives could be considered. 
* This is an open source project and all are encouraged to contribute.
* Its possible that the repo is not actively maintained.

## Support
Please enter an issue in the repo for any questions or problems. 
<br> Alternatively, please contact us at support@openfin.co
