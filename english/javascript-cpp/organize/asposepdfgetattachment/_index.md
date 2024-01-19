---
title: "AsposePdfGetAttachment"
second_title: Aspose.PDF for JavaScript via C++
description:  "Get attachment from a PDF-file."
type: docs
url: /javascript-cpp/organize/asposepdfgetattachment/
---

_Get attachment from a PDF-file._

```js
function AsposePdfGetAttachment(
    fileBlob,
    fileName,
    fileNameResult
)
```

**Parameters**: 
  * **fileBlob** Blob object 
  * **fileName** file name 
  * **fileNameResult** result file name template (for sample: "ResultPdfGetAttachment_{0}" where {0} - name of attachment) 

**Return**: 
JSON object 
  * **errorCode** - code error (0 no error)
  * **errorText** - text error ("" no error)
  * **filesCount** - attachment files count
  * **filesNameResult** - array of result filenames


**Web Worker example**:
```js
  /*Create Web Worker*/
  const AsposePDFWebWorker = new Worker("AsposePDFforJS.js");
  AsposePDFWebWorker.onerror = evt => console.log(`Error from Web Worker: ${evt.message}`);
  AsposePDFWebWorker.onmessage = evt => document.getElementById('output').textContent = 
    (evt.data == 'ready') ? 'loaded!' :
      (evt.data.json.errorCode == 0) ? 
        `Files(attachment) count: ${evt.data.json.filesCount.toString()}\n${evt.data.params.forEach(
          (element, index) => DownloadFile(evt.data.json.filesNameResult[index], "", element) ) ?? ""}` : 
        `Error: ${evt.data.json.errorText}`;

  /*Event handler*/
  const ffileGetAttachment = e => {
    const file_reader = new FileReader();
    file_reader.onload = event => {
      /*Get attachment from a PDF-file with template "ResultPdfGetAttachment_{0}" ({0} - name of attachment) and save*/
      AsposePDFWebWorker.postMessage({ "operation": 'AsposePdfGetAttachment', "params": [event.target.result, e.target.files[0].name, "ResultPdfGetAttachment_{0}"] }, [event.target.result]);
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
  var ffileGetAttachment = function (e) {
    const file_reader = new FileReader();
    file_reader.onload = (event) => {
      /*Get attachment from a PDF-file with template "ResultPdfGetAttachment_{0}" ({0} - name of attachment) and save*/
      const json = AsposePdfGetAttachment(event.target.result, e.target.files[0].name, "ResultPdfGetAttachment_{0}");
      if (json.errorCode == 0) {
        document.getElementById('output').textContent = "Files(attachment) count: " + json.filesCount.toString();
        /*Make links to result files*/
        for (let fileIndex = 0; fileIndex < json.filesCount; fileIndex++) DownloadFile(json.filesNameResult[fileIndex], "");
      }
      else document.getElementById('output').textContent = json.errorText;
    }
    file_reader.readAsArrayBuffer(e.target.files[0]);
  }
```
