---
title: "AsposePdfGetPagesLayers"
second_title: Aspose.PDF for JavaScript via C++
description: "Get list layers from a PDF-file."
type: docs
url: /javascript-cpp/metadata/asposepdfgetpageslayers/
---

_Get list layers from a PDF-file._

```js
function AsposePdfGetPagesLayers(
    fileBlob,
    fileName
)
```

**Parameters**: 

* **fileBlob** Blob object 
* **fileName** file name 

**Return**: 

JSON object 

* **errorCode** - code error (0 no error)
* **errorText** - text error ("" no error)
* **pagesLayers[][]** - list of pages with lists of layers on each page


**Web Worker example**:
```js
  /*Create Web Worker*/
  const AsposePDFWebWorker = new Worker("AsposePDFforJS.js");
  AsposePDFWebWorker.onerror = evt => console.log(`Error from Web Worker: ${evt.message}`);
  AsposePDFWebWorker.onmessage = evt => document.getElementById('output').textContent = 
    (evt.data == 'ready') ? 'loaded!' :
      (evt.data.json.errorCode == 0) ? `first page layers:\n${JSON.stringify(evt.data.json.pagesLayers[0], null, 4)}` : `Error: ${evt.data.json.errorText}`; 

  /*Event handler*/
  const ffilePdfGetPagesLayers = e => {
    const file_reader = new FileReader();
    file_reader.onload = event => {
      /*Get list layers from a PDF-file - Ask Web Worker*/
      AsposePDFWebWorker.postMessage({ "operation": 'AsposePdfGetPagesLayers', "params": [event.target.result, e.target.files[0].name] }, [event.target.result]);
    };
    file_reader.readAsArrayBuffer(e.target.files[0]);
  };
```
**Simple example**:
```js
  var ffilePdfGetPagesLayers = function (e) {
    const file_reader = new FileReader();
    file_reader.onload = (event) => {
      /*Get list layers from a PDF-file*/
      const json = AsposePdfGetPagesLayers(event.target.result, e.target.files[0].name);
      if (json.errorCode == 0) document.getElementById('output').textContent = "JSON:\n" + JSON.stringify(json, null, 4);
      else document.getElementById('output').textContent = json.errorText;
    };
    file_reader.readAsArrayBuffer(e.target.files[0]);
  };
```
