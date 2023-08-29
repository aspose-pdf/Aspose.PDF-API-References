---
title: "AsposePdfGetInfo"
second_title: Aspose.PDF for JavaScript via C++
description: "Get info (metadata) from a PDF-file."
type: docs
url: /javascript-cpp/metadata/asposepdfgetinfo/
---

_Get info (metadata) from a PDF-file._

```js
function AsposePdfGetInfo(
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
* **title** - title
* **creator** - creator
* **author** - author
* **subject** - subject
* **keywords** - keywords
* **creation** - creation date
* **mod** - modify date
* **format** - PDF format
* **version** - PDF version
* **ispdfa** - PDF is PDF/A
* **ispdfua** - PDF is PDF/UA
* **permission** - PDF permission
* **size** - PDF page size
* **pagecount** - Page count


**Example**:

```js
  var ffilePdfGetInfo = function (e) {
    const file_reader = new FileReader();
    file_reader.onload = (event) => {
      /*Get info (metadata) from a PDF-file*/
      const json = AsposePdfGetInfo(event.target.result, e.target.files[0].name);
      if (json.errorCode == 0) document.getElementById('output').textContent = "JSON:\n" + JSON.stringify(json, null, 4);
      else document.getElementById('output').textContent = json.errorText;
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
        `info:\n${JSON.stringify(evt.data.json, null, 4)}` :
        `Error: ${evt.data.json.errorText}`; 

  /*Event handler*/
  const ffilePdfGetInfo = e => {
    const file_reader = new FileReader();
    file_reader.onload = event => {
      /*Get info (metadata) from a PDF-file - Ask Web Worker*/
      AsposePDFWebWorker.postMessage(
        { "operation": 'AsposePdfGetInfo', "params": [event.target.result, e.target.files[0].name] },
        [event.target.result]
      );
    };
    file_reader.readAsArrayBuffer(e.target.files[0]);
  };
```