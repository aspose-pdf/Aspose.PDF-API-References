---
title: "AsposePdfAddWatermark"
second_title: Aspose.PDF for JavaScript via C++
description: "Add watermark to a PDF-file."
type: docs
url: /javascript-cpp/organize/asposepdfaddwatermark/
---

_Add watermark to a PDF-file._

```js
function AsposePdfAddWatermark(
    fileBlob,
    fileName,
    text,
    fontName,
    fontSize,
    foregroundColor,
    xPosition,
    yPosition,
    rotation,
    isBackground,
    opacity,
    fileNameResult 
)
```

**Parameters**:

* **fileBlob** Blob object
* **fileName** file name
* **text** watermark text
* **fontName** font name
* **fontSize** font size
* **foregroundColor** text color (hexadecimal format "#RRGGBB", where RR-red, GG-green and BB-blue hexadecimal integers)
* **xPosition** x watermark position
* **yPosition** y watermark position
* **rotation** watermark rotation (0-360)
* **isBackground** background (1 or 0)
* **opacity** opacity (decimal)
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
  const ffileAddWatermark = e => {
    const file_reader = new FileReader();
    file_reader.onload = event => {
      const text = "Aspose PDF";
      const fontName = "Arial";
      const fontSize = 32;
      const foregroundColor = "#010101";
      const xPosition = 100;
      const yPosition = 100;
      const rotation = 45;
      const isBackground = 1;
      const opacity = 0.5;
      /*Add watermark to a PDF-file and save the "ResultPdfAddWatermark.pdf" - Ask Web Worker*/
      AsposePDFWebWorker.postMessage({ "operation": 'AsposePdfAddWatermark', "params": [event.target.result, e.target.files[0].name, text, fontName, fontSize, foregroundColor, xPosition, yPosition, rotation, isBackground, opacity, "ResultPdfAddWatermark.pdf"] }, [event.target.result]);
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
  var ffileAddWatermark = function (e) {
    const file_reader = new FileReader();
    file_reader.onload = (event) => {
      /*Add watermark to a PDF-file and save the "ResultPdfAddWatermark.pdf"*/
      const json = AsposePdfAddWatermark(event.target.result, e.target.files[0].name, "Aspose PDF", "Arial", 32, "#010101", 100, 100, 45, 1, 0.5, "ResultPdfAddWatermark.pdf");
      if (json.errorCode == 0) document.getElementById('output').textContent = json.fileNameResult;
      else document.getElementById('output').textContent = json.errorText;
      /*Make a link to download the result file*/
      DownloadFile(json.fileNameResult, "application/pdf");
    };
    file_reader.readAsArrayBuffer(e.target.files[0]);
  };
```
