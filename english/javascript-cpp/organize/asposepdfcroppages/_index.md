---
title: "AsposePdfCropPages"
second_title: Aspose.PDF for JavaScript via C++
description:  "Crop PDF-pages."
type: docs
url: /javascript-cpp/organize/asposepdfcroppages/
---

_Crop PDF-pages._

```js
function AsposePdfCropPages(
    fileBlob,
    fileName,
    margin,
    fileNameResult 
)
```

**Parameters**: 

* **fileBlob** Blob object
* **fileName** file name
* **margin** page margin
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
  const ffileCropPages = e => {
    const file_reader = new FileReader();
    file_reader.onload = event => {
      const margin = 0.5;
      /*Crop PDF-pages and save the "ResultPdfCropPages.pdf" - Ask Web Worker*/
      AsposePDFWebWorker.postMessage({ "operation": 'AsposePdfCropPages', "params": [event.target.result, e.target.files[0].name, margin, "ResultPdfCropPages.pdf"] }, [event.target.result]);
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
  var ffileCropPages = function (e) {
    const file_reader = new FileReader();
    file_reader.onload = (event) => {
      /*Crop PDF-pages and save the "ResultRotation.pdf"*/
      const json = AsposePdfCropPages(event.target.result, e.target.files[0].name, 0, "ResultPdfCropPages.pdf");
      if (json.errorCode == 0) document.getElementById('output').textContent = json.fileNameResult
      else document.getElementById('output').textContent = json.errorText;
      /*Make a link to download the result file*/
      DownloadFile(json.fileNameResult, "application/pdf");
    };
    file_reader.readAsArrayBuffer(e.target.files[0]);
  };
```
