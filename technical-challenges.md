## Botillo - Proposed Challenges

List with a brief description of the task/problem we want to solve.

## Technical

### ~~Debugging tech issues with google hangouts~~

#### Solution

* Check logs at [chrome://webrtc-logs](chrome://webrtc-logs)
* filesystem: [https://hangouts.google.com/temporary/log_v2](https://hangouts.google.com/temporary/log_v2)

### ~~Why is my computer slow?~~

#### Solution

* Check Activity Monitor

### ~~How can I improve the google sheets export workflow~~

#### Solution

* Google this: "five really handy google command line tricks"
* "Export sheet data" chrome plugin (exports to json)
* google-spreadsheet-to-json (npm)
* [Copytext](https://github.com/nprapps/copytext)

### ~~Better spreadsheet software than LibreOffice (Excel not an option)~~

#### Solution

* [Airtable.com](Airtable.com)

### ~~Best sublime text shortcuts~~

#### Solution

* Multicursor: Find term then CMD+D
* 2 Columns: CMD+OPT+2

### ~~Stop getting conflicts on built files on the repo~~

#### Solution

* Do not commit built files. Work on documentation so team members can rebuild without conflicts

### ~~How to scroll up with no limit output in terminal~~

#### Solution

* Output to file instead
* On mac Terminal -> Profile -> Terminal -> Check Unlimited Scrolling

### ~~Get statistics of a CSV file~~

#### Solution

* Python:
    * Pandas + jupyter
    * csvkit -> csvstats
* Google sheets has some tools for non coders
* R: Summary

### ~~How to resize all images in a folder~~

#### Solution

* Convert
* Mogrify
* Windows live photo gallery

### ~~Quick+Dirty way to extract phone preffix from phone without coding~~

#### Solution

* Search +  Replace + RegEx in text editor
* [OpenRefine](http://openrefine.org/)
* Text to columns in Google Spreadsheet or excel

### ~~How do I turn 26 million TIFF files into data (some handwritten)~~

#### Solution

* Tesseract-ocr + [Extract](https://github.com/ICIJ/extract) tool developed by ICIJ which integrate tesseract + redis + Apache Solr

### ~~How do I handle "Single Source of truth" Changing?~~

How to automate the pipeline + publish of a database

#### Solution

* [Luigi](https://pypi.python.org/pypi/luigi/2.2.0) python tool
* Talend data suite

### ~~How to convert shapefile into geojson for using on a webpage~~

#### Solution

* [Ogr2Ogr](http://www.gdal.org/ogr2ogr.html)
* [QGIS](http://www.qgis.org/en/site/)
* [Mapshaper.com](http://www.mapshaper.org/)

### ~~Automate the bootstrapping of a project (templating)~~

#### Solution

* [Yeoman](http://yeoman.io/)
* [NPR Opinionated App-template](https://github.com/nprapps/app-template)

### ~~How to split a pdf into single-page pdfs??~~

#### Solution

* Manually: Drag Page from sidebar into finder on Preview (Mac)
* PDF Split and Merge ([PDFSAM](http://www.pdfsam.org/))

### ~~Easy way to join pdfs together?~~

#### Solution

* MAC - [PDFPEN](https://smilesoftware.com/pdfpen)
* Open them all in preview: Print -> Save as PDF
* [PDFSAM](http://www.pdfsam.org/)
* Adobe Acrobat

### ~~Setting the working directory so that it's dynamic when changing computers?~~

#### Solution

* [Dropbox](https://www.dropbox.com/home)
* RelativePaths: "./"
* Home Folder: "~/"

### ~~Convert a csv file into a JSON file to be used in a web application~~

#### Description

A nice CSV file has arrived to our hands and we want to use it for our next web app, but it would be much easier for us to have it in a json format to handle it easily in Javascript.

Wouldn't it be nice to find a tool that does that conversion for us without too much hassle?

#### [Solution](csvjson/README.md)
