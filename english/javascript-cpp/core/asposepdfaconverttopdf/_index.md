---
title: "AsposePdfAConvertToPDF"
second_title: Aspose.PDF for JavaScript via C++
description:  "Convert a PDF/A-file to PDF."
type: docs
url: /javascript-cpp/core/asposepdfaconverttopdf/
---

_Convert a PDF/A-file to PDF._

```js
function AsposePdfAConvertToPDF(
    fileBlob,
    fileName,
    fileResultName 
)
```

**Parameters**: 

* **fileBlob** Blob object 
* **fileName** file name 
* **fileResultName** result file name 

**Return**: 
JSON object 
  * **errorCode** - code error (0 no error)
  * **errorText** - text error ("" no error)
  * **fileNameResult** - result file name


**Example**:
```js
  var ffilePdfAConvertToPDF = function (e) {
    const file_reader = new FileReader();
    file_reader.onload = (event) => {
      /*convert a PDF/A-file to PDF and save the "ResultConvertToPDF.pdf"*/
      const json = AsposePdfAConvertToPDF(event.target.result, e.target.files[0].name, "ResultConvertToPDF.pdf");
      if (json.errorCode == 0) document.getElementById('output').textContent = json.fileNameResult;
      else document.getElementById('output').textContent = json.errorText;
      /*make a link to download the result file*/
      DownloadFile(json.fileNameResult, "application/pdf");
    };
    file_reader.readAsArrayBuffer(e.target.files[0]);
  };
```
**Web Worker**:
```js
  /*Create Web Worker*/
  const AsposePDFWebWorker = new Worker("AsposePDFforJS.js");
  AsposePDFWebWorker.onerror = evt => console.log(`Error from Web Worker: ${evt.message}`);
  AsposePDFWebWorker.onmessage = evt => document.getElementById('output').textContent = 
    (evt.data == 'ready') ? 'loaded!' :
      (evt.data.json.errorCode == 0) ?
        `Result:\n${DownloadFile(evt.data.json.fileNameResult, "application/pdf", evt.data.params[0])}` :
        `Error: ${evt.data.json.errorText}`;

  /*Event handler*/
  const ffilePdfAConvertToPDF = e => {
    const file_reader = new FileReader();
    file_reader.onload = event => {
      /*convert a PDF/A-file to PDF and save the "ResultConvertToPDF.pdf" - Ask Web Worker*/
      AsposePDFWebWorker.postMessage(
        { "operation": 'AsposePdfAConvertToPDF', "params": [event.target.result, e.target.files[0].name, "ResultConvertToPDF.pdf"] },
        [event.target.result]
      );
    };
    file_reader.readAsArrayBuffer(e.target.files[0]);
  };

  /*make a link to download the result file*/
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
