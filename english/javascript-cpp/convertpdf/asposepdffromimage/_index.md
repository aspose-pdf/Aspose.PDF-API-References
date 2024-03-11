---
title: "AsposePdfFromImage"
second_title: Aspose.PDF for JavaScript via C++
description:  "Convert a Image-file to PDF."
type: docs
url: /javascript-cpp/convertpdf/asposepdffromimage/
---

_Convert a Image-file to PDF._

```js
function AsposePdfFromImage(
    fileBlob,
    fileName,
    pdfPageSize,
    margin,
    isLandscape,
    fileNameResult 
)
```

**Parameters**: 

* **fileBlob** Blob object 
* **fileName** image file name (support bmp, jpeg, png, tiff, gif formats)
* **pdfPageSize**  page size:
  * Module.PdfPageSize.A0
  * Module.PdfPageSize.A1
  * Module.PdfPageSize.A2
  * Module.PdfPageSize.A3
  * Module.PdfPageSize.A4
  * Module.PdfPageSize.A5
  * Module.PdfPageSize.A6
  * Module.PdfPageSize.B5
  * Module.PdfPageSize.PageLetter
  * Module.PdfPageSize.PageLegal
  * Module.PdfPageSize.PageLedger
  * Module.PdfPageSize.P11x17
  * Module.PdfPageSize.ImageSize
* **margin** page margin
* **isLandscape** page landscape mode (0 or 1)
* **fileNameResult** result file name 

**Return**: 
JSON object 
  * **errorCode** - code error (0 no error)
  * **errorText** - text error ("" no error)
  * **fileNameResult** - result file name


**Web Worker example**:
```js
  /*Create Web Worker*/
  const AsposePDFWebWorker = new Worker("AsposePDFforJS.js");
  AsposePDFWebWorker.onerror = evt => console.log(`Error from Web Worker: ${evt.message}`);
  AsposePDFWebWorker.onmessage = evt => document.getElementById('output').textContent = 
    (evt.data == 'ready') ? 'loaded!' :
      (evt.data.json.errorCode == 0) ? `Result:\n${DownloadFile(evt.data.json.fileNameResult, "application/pdf", evt.data.params[0])}` : `Error: ${evt.data.json.errorText}`;

  /*Event handler*/
  const ffileFromImage = e => {
    const file_reader = new FileReader();
    file_reader.onload = event => {
      /*Convert a Image-file to PDF and save the "ResultPDFFromImage.pdf" - Ask Web Worker*/
      AsposePDFWebWorker.postMessage({ "operation": 'AsposePdfFromImage', "params": [event.target.result, e.target.files[0].name, 'Module.PdfPageSize.A4', 0, true, "ResultPDFFromImage.pdf"] }, [event.target.result]);
    };
    file_reader.readAsArrayBuffer(e.target.files[0]);
  };

  /*Make a link to download the result file*/
  const DownloadFile = (filename, mime, content) => {
      mime = mime || "application/octet-stream";
      var link = document.createElement("a"); 
      link.href = URL.createObjectURL(new Blob([content], {type: mime}));
      link.download = filename;
      link.innerHTML = "Click here to download the file " + filename;
      document.body.appendChild(link); 
      document.body.appendChild(document.createElement("br"));
      return filename;
    }
```
**Simple example**:
```js
  var ffileFromImage = function (e) {
    const file_reader = new FileReader();
    file_reader.onload = (event) => {
      /*Convert a Image-file to PDF and save the "ResultPDFFromImage.pdf"*/
      const json = AsposePdfFromImage(event.target.result, e.target.files[0].name, Module.PdfPageSize.A4, 10, false, "ResultPDFFromImage.pdf");
      if (json.errorCode == 0) document.getElementById('output').textContent = json.fileNameResult;
      else document.getElementById('output').textContent = json.errorText;
      /*Make a link to download the result file*/
      DownloadFile(json.fileNameResult, "application/pdf");
    }
    file_reader.readAsArrayBuffer(e.target.files[0]);
  }
```
