---
title: "AsposePdfSetBackgroundColor"
second_title: Aspose.PDF for JavaScript via C++
description:  "Set the background color for the PDF-file."
type: docs
url: /javascript-cpp/organize/asposepdfsetbackgroundcolor/
---

_Set the background color for the PDF-file._

```js
function AsposePdfSetBackgroundColor(
    fileBlob,
    fileName,
    backgroundColor,
    fileNameResult
)
```

**Parameters**: 

* **fileBlob** Blob object 
* **fileName** file name 
* **backgroundColor** PDF background color (hexadecimal format "#RRGGBB", where RR-red, GG-green and BB-blue hexadecimal integers)
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
  const ffilePdfSetBackgroundColor = e => {
    const file_reader = new FileReader();
    file_reader.onload = event => {
      const backgroundColor= "#426bf4";
      /*Set the background color for the PDF-file and save the "ResultPdfSetBackgroundColor.pdf" - Ask Web Worker*/
      AsposePDFWebWorker.postMessage({ "operation": 'AsposePdfSetBackgroundColor', "params": [event.target.result, e.target.files[0].name, backgroundColor, "ResultPdfSetBackgroundColor.pdf"] }, [event.target.result]);
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
  var ffilePdfSetBackgroundColor = function (e) {
    const file_reader = new FileReader();
    file_reader.onload = (event) => {
      /*Set the background color for the PDF-file and save the "ResultPdfSetBackgroundColor.pdf"*/
      const json = AsposePdfSetBackgroundColor(event.target.result, e.target.files[0].name, "#426bf4", "ResultPdfSetBackgroundColor.pdf");
      if (json.errorCode == 0) document.getElementById('output').textContent = json.fileNameResult
      else document.getElementById('output').textContent = json.errorText;
      /*Make a link to download the result file*/
      DownloadFile(json.fileNameResult, "application/pdf");
    };
    file_reader.readAsArrayBuffer(e.target.files[0]);
  };
```
