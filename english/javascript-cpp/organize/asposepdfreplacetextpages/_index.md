---
title: "AsposePdfReplaceTextPages"
second_title: Aspose.PDF for JavaScript via C++
description: "Replace text on pages in a PDF-file."
type: docs
url: /javascript-cpp/organize/asposepdfreplacetextpages/
---

_Replace text on pages in a PDF-file._

```js
function AsposePdfReplaceTextPages(
    fileBlob,
    fileName,
    findText,
    replaceText,
    numPages,
    fileNameResult
)
```

**Parameters**: 

* **fileBlob** Blob object 
* **fileName** file name 
* **findText** text fragment to search
* **replaceText** text fragment to replace
* **numPages** page numbers:
  * string, include page numbers with intervals as "7, 20, 22, 30-32, 33, 36-40, 46"
  * array, array of page numbers, such as [1,3]
  * number, page number as 2
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
  const ffileReplaceTextPages = e => {
    const file_reader = new FileReader();
    file_reader.onload = event => {
      const findText = 'Aspose';
      const replaceText = 'ASPOSE';

      /*string, include number pages with interval: "7, 20, 22, 30-32, 33, 36-40, 46"*/
      const numPages = "1-3";
      /*array, array of number pages*/
      /*const numPages = [1,3];*/
      /*number, number page*/
      /*const numPages = 1;*/
      /*if numPages == 0 then all pages*/

      /*Replace text on 1-3 pages in a PDF-file and save the "ResultReplaceTextPages.pdf" - Ask Web Worker*/
      AsposePDFWebWorker.postMessage({ "operation": 'AsposePdfReplaceTextPages', "params": [event.target.result, e.target.files[0].name, findText, replaceText, numPages, "ResultReplaceTextPages.pdf"] }, [event.target.result]);
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
  var ffileReplaceTextPages = function (e) {
    const file_reader = new FileReader();
    file_reader.onload = (event) => {

      /*string, include number pages with interval: "7, 20, 22, 30-32, 33, 36-40, 46"*/
      const numPages = "1-3";
      /*array, array of number pages*/
      /*const numPages = [1,3];*/
      /*number, number page*/
      /*const numPages = 1;*/
      /*if numPages == 0 then all pages*/

      /*Replace text on 1-3 pages in a PDF-file and save the "ResultReplaceTextPages.pdf"*/
      const json = AsposePdfReplaceTextPages(event.target.result, e.target.files[0].name, "Aspose", "ASPOSE", numPages, "ResultReplaceTextPages.pdf");
      if (json.errorCode == 0) document.getElementById('output').textContent = json.fileNameResult
      else document.getElementById('output').textContent = json.errorText;
      /*Make a link to download the result file*/
      DownloadFile(json.fileNameResult, "application/pdf");
    };
    file_reader.readAsArrayBuffer(e.target.files[0]);
  };
```
