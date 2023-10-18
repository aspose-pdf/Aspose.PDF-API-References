---
title: "AsposePdfPagesToSvg"
second_title: Aspose.PDF for JavaScript via C++
description:  "Convert a PDF-file to SVG."
type: docs
url: /javascript-cpp/convert/asposepdfpagestosvg/
---

_Convert a PDF-file to SVG._

```
function AsposePdfPagesToSvg(
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
  * **filesCount** - png files count
  * **filesNameResult** - array of result filenames


**Web Worker example**:
```js
  /*Create Web Worker*/
  const AsposePDFWebWorker = new Worker("AsposePDFforJS.js");
  AsposePDFWebWorker.onerror = evt => console.log(`Error from Web Worker: ${evt.message}`);
  AsposePDFWebWorker.onmessage = evt => document.getElementById('output').textContent = 
    (evt.data == 'ready') ? 'loaded!' :
      (evt.data.json.errorCode == 0) ? 
        `Files(pages) count: ${evt.data.json.filesCount.toString()}\n${evt.data.params.forEach(
          (element, index) => DownloadFile(evt.data.json.filesNameResult[index], "image/svg", element) ) ?? ""}` : 
        `Error: ${evt.data.json.errorText}`;

  /*Event handler*/
  const ffileToSvg = e => {
    const file_reader = new FileReader();
    file_reader.onload = event => {
      /*Convert a PDF-file to SVG - Ask Web Worker*/
      AsposePDFWebWorker.postMessage({ "operation": 'AsposePdfPagesToSvg', "params": [event.target.result, e.target.files[0].name, "ResultPdfToSvg.svg"] }, [event.target.result]);
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
  var ffileToSvg = function (e) {
    const file_reader = new FileReader();
    file_reader.onload = (event) => {
      /*Convert a PDF-file to SVG*/
      const json = AsposePdfPagesToSvg(event.target.result, e.target.files[0].name, "ResultPdfToSvg.svg");
      if (json.errorCode == 0) {
        document.getElementById('output').textContent = "Files(pages) count: " + json.filesCount.toString();
        /*Make links to result files*/
        for (let fileIndex = 0; fileIndex < json.filesCount; fileIndex++) DownloadFile(json.filesNameResult[fileIndex], "image/svg");
      }
      else document.getElementById('output').textContent = json.errorText;
    }
    file_reader.readAsArrayBuffer(e.target.files[0]);
  }
```
