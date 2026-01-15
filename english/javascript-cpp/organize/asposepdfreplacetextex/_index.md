---
title: "AsposePdfReplaceTextEx"
second_title: Aspose.PDF for JavaScript via C++
description: "Replace text in a PDF-file with alignment control."
type: docs
url: /javascript-cpp/organize/asposepdfreplacetextex/
---

_Replace text in a PDF-file with alignment control._

```js
function AsposePdfReplaceTextEx(
    fileBlob,
    fileName,
    findText,
    replaceText,
    options,
    fileNameResult
)
```

**Parameters**: 

* **fileBlob** Blob object
* **fileName** file name
* **findText** text fragment to search
* **replaceText** text fragment to replace
* **options** object, settings for text replacement:
  * `alignment` (string), text alignment (e.g., "left", "right", "auto")
  * `numPages` (string|number|Array), target pages to process:
    * number, page number as 2
    * string, include page numbers with intervals as "7, 20, 22, 30-32, 33, 36-40, 46"
    * Array, array of page numbers, such as [1,3]
  Pass an empty object `{}` for default behavior
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
  const ffileReplaceTextEx = e => {
    const file_reader = new FileReader();
    file_reader.onload = event => {
      const findText = 'Aspose';
      const replaceText = 'ASPOSE';
      const optionsText = {numPages: 1, alignment: "auto"};
      /*Replace text in a PDF-file with alignment control and save the "ResultReplaceTextEx.pdf" - Ask Web Worker*/
      AsposePDFWebWorker.postMessage({ "operation": 'AsposePdfReplaceTextEx', "params": [event.target.result, e.target.files[0].name, findText, replaceText, optionsText, "ResultReplaceTextEx.pdf"] }, [event.target.result]);
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
  var ffileReplaceTextEx = function (e) {
    const file_reader = new FileReader();
    file_reader.onload = (event) => {
      /*Replace text in a PDF-file with alignment control and save the "ResultReplaceTextEx.pdf"*/
      const json = AsposePdfReplaceTextEx(event.target.result, e.target.files[0].name, "Aspose", "ASPOSE", {alignment: "left"}, "ResultReplaceTextEx.pdf");
      if (json.errorCode == 0) document.getElementById('output').textContent = json.fileNameResult
      else document.getElementById('output').textContent = json.errorText;
      /*Make a link to download the result file*/
      DownloadFile(json.fileNameResult, "application/pdf");
    };
    file_reader.readAsArrayBuffer(e.target.files[0]);
  };
```
