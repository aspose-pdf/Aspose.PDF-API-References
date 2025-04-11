---
title: "AsposePdfValidatePDFA"
second_title: Aspose.PDF for JavaScript via C++
description:  "Validate PDF/A compatibility a PDF-file."
type: docs
url: /javascript-cpp/organize/asposepdfvalidatepdfa/
---

_Validate PDF/A compatibility a PDF-file._

```js
function AsposePdfValidatePDFA(
    fileBlob,
    fileName,
    pdfFormat,
    fileNameResult 
)
```

**Parameters**: 

* **fileBlob** Blob object
* **fileName** file name
* **pdfFormat** format PDF/A:
  * Module.PdfFormat.PDF_A_1A
  * Module.PdfFormat.PDF_A_1B
  * Module.PdfFormat.PDF_A_2A
  * Module.PdfFormat.PDF_A_3A
  * Module.PdfFormat.PDF_A_2U
  * Module.PdfFormat.PDF_A_3B
  * Module.PdfFormat.PDF_A_3U
* **fileNameResult** result file name where verification comments will be stored (xml format)

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
      (evt.data.json.errorCode == 0) ? `Result:\n${DownloadFile(evt.data.json.fileNameResult, "application/xml", evt.data.params[0])}` : `Error: ${evt.data.json.errorText}`;

  /*Event handler*/
  const ffilePdfValidatePDFA = e => {
    const file_reader = new FileReader();
    file_reader.onload = event => {
      const pdfFormat = 'Module.PdfFormat.PDF_A_1A';
      /*Validate PDF/A compatibility a PDF-file and save result in the "ResultPdfValidatePDFA.xml" - Ask Web Worker*/
      AsposePDFWebWorker.postMessage({ "operation": 'AsposePdfValidatePDFA', "params": [event.target.result, e.target.files[0].name, pdfFormat, "ResultPdfValidatePDFA.xml"] }, [event.target.result]);
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
var ffilePdfValidatePDFA = function (e) {
    const file_reader = new FileReader();
    file_reader.onload = (event) => {
      /*Validate PDF/A compatibility a PDF-file and save result in the "ResultPdfValidatePDFA.xml"*/
      const json = AsposePdfValidatePDFA(event.target.result, e.target.files[0].name, Module.PdfFormat.PDF_A_1A, "ResultPdfValidatePDFA.xml");
      if (json.errorCode == 0) document.getElementById('output').textContent = json.fileNameResult
      else document.getElementById('output').textContent = json.errorText;
      /*Make a link to download the result file*/
      DownloadFile(json.fileNameResult, "application/xml");
    };
    file_reader.readAsArrayBuffer(e.target.files[0]);
  };
```
