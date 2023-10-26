---
title: "AsposePdfPrepare"
second_title: Aspose.PDF for JavaScript via C++
description:  "Save the BLOB in the Memory FS for processing."
type: docs
url: /javascript-cpp/core/asposepdfprepare/
---

_Save the BLOB in the Memory FS for processing._

```js
function AsposePdfPrepare(
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
  * **fileNameResult** - result file name


**Web Worker example**:
```js
  /*Create Web Worker*/
  const AsposePDFWebWorker = new Worker("AsposePDFforJS.js");
  AsposePDFWebWorker.onerror = evt => console.log(`Error from Web Worker: ${evt.message}`);
  AsposePDFWebWorker.onmessage = evt => document.getElementById('output').textContent = 
    (evt.data == 'ready') ? 'loaded!' :
      (evt.data.json.errorCode == 0) ?
        `Result:\n${(evt.data.operation == 'AsposePdfPrepare') ?
          'Saved the BLOB to memory FS for processing':
          '...main operation, see AsposePdfAddImage as an example...'}` :
        `Error: ${evt.data.json.errorText}`;

  /*Event handler*/
  const ffileImage = e => {
    const file_reader = new FileReader();
    file_reader.onload = event => {
      /*Save the BLOB in the Memory FS for processing*/
      AsposePDFWebWorker.postMessage(
        { "operation": 'AsposePdfPrepare', "params": [event.target.result, e.target.files[0].name] },
        [event.target.result]
      );
    };
    file_reader.readAsArrayBuffer(e.target.files[0]);
  };
```
**Simple example**:
```js
  var ffileImage = function (e) {
    const file_reader = new FileReader();
    /*Set the image filename*/
    const fileImage = e.target.files[0].name;
    file_reader.onload = (event) => {
      /*Save the BLOB in the Memory FS for processing*/
      AsposePdfPrepare(event.target.result, fileImage);
    };
    file_reader.readAsArrayBuffer(e.target.files[0]);
  };
```
