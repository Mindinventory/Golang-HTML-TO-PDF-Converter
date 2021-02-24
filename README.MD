# Golang HTML to PDF Converter
<a href="https://travis-ci.org/Mindinventory/Golang-HTML-TO-PDF-Converter" style="pointer-events: none;" target="_blank"><img src="https://travis-ci.org/Mindinventory/Golang-HTML-TO-PDF-Converter.svg?branch=master"></a>
<a href="https://godoc.org/fyne.io/fyne" style="pointer-events: none;" target="_blank"><img src="https://img.shields.io/badge/go-documentation-blue.svg"></a>
<a href="https://goreportcard.com/report/github.com/Mindinventory/Golang-HTML-TO-PDF-Converter" style="pointer-events: none;" target="_blank"><img src="https://goreportcard.com/badge/github.com/Mindinventory/Golang-HTML-TO-PDF-Converter"></a>
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/mindinventory/Golang-HTML-TO-PDF-Converter/blob/master/LICENSE)

For reading any document, one prefers PDF format over any other formats as it is considered as a standard format for any document in our day to day life. We often come across converting any form details or previews on the website in the form of HTML to PDF. For GoLang, understanding such usability, Developers at Mindinventory made an effort for making one HTML to PDF Converter which can be used for converting HTML content to PDF.


## What it is?

It is a repository, integrating which one can offer HTML to PDF Conversion to their customers. 

## Prerequisite

Install wkhtmltopdf using below command 
  - ``sudo apt install wkhtmltopdf`` - for Ubuntu
  - ``brew install Caskroom/cask/wkhtmltopdf`` - For Mac


## Steps to Follow

<img src="https://raw.githubusercontent.com/Mindinventory/Golang-HTMLTOPDF-Converter/master/html-pdf-new.gif" >


  1. Create a sample HTML file inside of your project.
  
  2. Get go package using the below command for parsing the HTMl template.
     - ``go get github.com/SebastiaanKlippert/go-wkhtmltopdf``
   
  3. Get another go package for converting this html parse data to pdf using the below command.    
     - ``go get html/template``
     
  4. Run below command 
     - ``go run main.go``

###The previous version of golang was deprecated and not supporting the converter library so dependencies are updated with the new updates.

#Steps by step:

- Install ``golang (1.16)``
- Check ``go version`` (Make Sure it is latest = 1.16)
- ``go mod vendor``
- ``go build``


##To Run the project:

- ``go run main.go``

## Update project dependencies 

- ``go get github.com/SebastiaanKlippert/go-wkhtmltopdf`` v1.6.1
- ``go get html/template``


After finish above steps, You can generate pdf file from html. 

**NOTES:** The pdf will be generated in the storage directory. Don't forget to mention your html and pdf path details inside your code. If you want to generate pdf for static data then it is not mandatory to generate another html for clone data. Use that same sample html inside the code.


## LICENSE!

Golang HTML to PDF Converter is [MIT-licensed](https://github.com/mindinventory/Golang-HTMLTOPDF-Converter/blob/master/LICENSE)

## Let us know!
We’d be really happy if you sent us links to your projects where you use our component. Just send an email to sales@mindinventory.com And do let us know if you have any questions or suggestion regarding our work.
