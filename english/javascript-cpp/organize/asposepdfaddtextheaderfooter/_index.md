---
title: "AsposePdfAddTextHeaderFooter"
second_title: Aspose.PDF for JavaScript via C++
description: "Add text in Header/Footer of a PDF-file."
type: docs
url: /javascript-cpp/organize/asposepdfaddtextheaderfooter/
---

_Add text in Header/Footer of a PDF-file._

```js
function AsposePdfAddTextHeaderFooter(
    fileBlob,
    fileName,
    header, 
    footer,
    fileResultName
)
```

**Parameters**: 

* **fileBlob** Blob object 
* **fileName** file name 
* **header** page header, if not need to set, use undefined or "" (empty string)
* **footer** page footer, if not need to set, use undefined or "" (empty string)
* **fileResultName** result file name 

**Return**: 

JSON object 

* **errorCode** - code error (0 no error)
* **errorText** - text error ("" no error)
* **fileNameResult** - result file name


**Example**:

```js
  var ffileAddTextHeaderFooter = function (e) {
    const file_reader = new FileReader();
    file_reader.onload = (event) => {
      /*Add text in Header/Footer of a PDF-file and save the "ResultAddHeader.pdf"*/
      const json = AsposePdfAddTextHeaderFooter(event.target.result, e.target.files[0].name, "Aspose.PDF for JavaScript via C++", "", "ResultAddHeader.pdf");
      if (json.errorCode == 0) document.getElementById('output').textContent = json.fileNameResult;
      else document.getElementById('output').textContent = json.errorText;
      /*Make a link to download the result file*/
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
  const ffileAddTextHeaderFooter = e => {
    const file_reader = new FileReader();
    file_reader.onload = event => {
      const header = 'Aspose.PDF for JavaScript via C++';
      const footer = 'ASPOSE';
      /*Add text in Header/Footer of a PDF-file and save the "ResultAddHeaderFooter.pdf" - Ask Web Worker*/
      AsposePDFWebWorker.postMessage(
        { "operation": 'AsposePdfAddTextHeaderFooter',
          "params": [event.target.result, e.target.files[0].name, header, footer, "ResultAddHeaderFooter.pdf"] },
        [event.target.result]
      );
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