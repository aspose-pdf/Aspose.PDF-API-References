---
title: "AsposePdfMakeNUp"
second_title: Aspose.PDF for JavaScript via C++
description:  "Make N-Up document from a PDF-file"
type: docs
url: /javascript-cpp/organize/asposepdfmakenup/
---

_Make N-Up document from a PDF-file_

```js
function AsposePdfMakeNUp(
    fileBlob,
    fileName,
    columns,
    rows,
    fileNameResult 
)
```

**Parameters**: 

* **fileBlob** Blob object
* **fileName** file name
* **columns** count of columns
* **rows** count of rows
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
  const ffileMakeNUp = e => {
    const file_reader = new FileReader();
    file_reader.onload = event => {
      /*Make N-Up document from a PDF-file and save the "ResultMakeNUp.pdf" - Ask Web Worker*/
      const columns = 2
      const rows = 2
      AsposePDFWebWorker.postMessage({ "operation": 'AsposePdfMakeNUp', "params": [event.target.result, e.target.files[0].name, columns, rows, "ResultMakeNUp.pdf"] }, [event.target.result]);
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
  var ffileMakeNUp = function (e) {
    const file_reader = new FileReader();
    file_reader.onload = (event) => {
      /*Make N-Up document from a PDF-file and save the "ResultMakeNUp.pdf"*/
      const columns = 2
      const rows = 2
      const json = AsposePdfMakeNUp(event.target.result, e.target.files[0].name, columns, rows, "ResultMakeNUp.pdf");
      if (json.errorCode == 0) document.getElementById('output').textContent = json.fileNameResult
      else document.getElementById('output').textContent = json.errorText;
      /*Make a link to download the result file*/
      DownloadFile(json.fileNameResult, "application/pdf");
    };
    file_reader.readAsArrayBuffer(e.target.files[0]);
  };
```
