# pdf-PRINTER<sub>(chrome)</sub>
pdf-PRINTER is a HTML page you can use to save PDFs. It can be saved as a bookmark on Google Chrome.  
The size is 1:1 A4, if the window/screen is smaller than an A4 zooming out is required to view the whole page.  
Also, when saving the PDF make sure to only select the first page!

### How to use
* right click `Bookmarks bar` > `Add page...` > `URL`: [pdf-PRINTER-bookmark](https://raw.githubusercontent.com/daniel-barbu/pdf-PRINTER/master/pdf-PRINTER-bookmark)  
or
* I host it [here](https://daniel-barbu.cf/files/pdf-PRINTER.html).

### Controls
| any element (dbclick) | remove it          |
|:----------------------|:-------------------|
| a                     | lower font size    |
| A                     | increase font size |
| X (dbclick)           | save mode          |

### Screenshot
[example PDF output](https://github.com/daniel-barbu/pdf-PRINTER/raw/master/img/output.pdf)
![/img/screenshot.png not loaded correctly](/img/screenshot.png)

<script>
  document.body.innerHTML="";
  var iFrame=document.createElement("iframe"); document.body.appendChild(iFrame); iFrame.src="https://pdf.daniel-barbu.cf/pdf-PRINTER.html";
  iFrame.width="100%"; iFrame.height="100%"; iFrame.style.position="absolute"; iFrame.style.border="0px";
</script>
