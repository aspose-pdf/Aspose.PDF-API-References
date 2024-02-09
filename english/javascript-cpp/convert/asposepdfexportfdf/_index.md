---
title: "AsposePdfExportFdf"
second_title: Aspose.PDF for JavaScript via C++
description:  "Export from a PDF-file with AcroForm to FDF"
type: docs
url: /javascript-cpp/convert/asposepdfexportfdf/
---

_Export from a PDF-file with AcroForm to FDF._

```js
function AsposePdfExportFdf(
    fileBlob,
    fileName,
    fileNameResult 
)
```

**Parameters**: 

* **fileBlob** Blob object 
* **fileName** file name 
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
      (evt.data.json.errorCode == 0) ? `Result:\n${DownloadFile(evt.data.json.fileNameResult, "application/vnd.fdf", evt.data.params[0])}` : `Error: ${evt.data.json.errorText}`;

  /*Event handler*/
  const ffileExportfdf = e => {
    const file_reader = new FileReader();
    file_reader.onload = event => {
      /*Export from a PDF-file with AcroForm to FDF and save the "ResultPDFExportFdf.fdf" - Ask Web Worker*/
      AsposePDFWebWorker.postMessage({ "operation": 'AsposePdfExportFdf', "params": [event.target.result, e.target.files[0].name, "ResultPDFExportFdf.fdf"] }, [event.target.result]);
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
  var ffileExportFdf = function (e) {
    const file_reader = new FileReader();
    file_reader.onload = (event) => {
      /*Export from a PDF-file with AcroForm to FDF and save the "ResultPDFExportFdf.fdf"*/
      const json = AsposePdfExportFdf(event.target.result, e.target.files[0].name, "ResultPDFExportFdf.fdf");
      if (json.errorCode == 0) document.getElementById('output').textContent = json.fileNameResult;
      else document.getElementById('output').textContent = json.errorText;
      /*Make a link to download the result file*/
      DownloadFile(json.fileNameResult, "application/vnd.fdf");
    }
    file_reader.readAsArrayBuffer(e.target.files[0]);
  }
```
