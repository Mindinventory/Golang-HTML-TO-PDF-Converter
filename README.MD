# Golang HTML to PDF Converter

<img src="https://raw.githubusercontent.com/Mindinventory/Golang-HTMLTOPDF-Converter/master/html-pdf-new.gif" >

## Follow below steps to generate HTML to PDF using Golang:

  1. Create a sample HTML file inside of your project.
  
  2. Make sure to download the below library in your system using the following command.  
     
     - ``sudo apt install wkhtmltopdf`` - for Ubuntu
     - ``brew install Caskroom/cask/wkhtmltopdf`` - For Mac
  
  3. Download go package using the below command for parsing the HTMl template.
     - ``go get github.com/SebastiaanKlippert/go-wkhtmltopdf``
   
  4. We need to download another package for converting this html parse data to pdf using the below command.    
     - ``go get html/template``
     
  5. Run 
     - ``go run main.go``
     
       
 
  
After finish above steps, You can generate pdf file from html. 

**NOTES:** Don't forget to mention your html and pdf path details inside your code. If you want to generate pdf for static data then it is not mandatory to generate another html for clone data. Use that same sample html inside the code.


## LICENSE!

Golang HTML to PDF Converter is [MIT-licensed](https://github.com/mindinventory/Golang-HTMLTOPDF-Converter/blob/master/LICENSE)

## Let us know!
We’d be really happy if you sent us links to your projects where you use our component. Just send an email to sales@mindinventory.com And do let us know if you have any questions or suggestion regarding our work.
