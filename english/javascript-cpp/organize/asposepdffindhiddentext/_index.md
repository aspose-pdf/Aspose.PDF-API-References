---
title: "AsposePdfFindHiddenText"
second_title: Aspose.PDF for JavaScript via C++
description: "Find hidden text in a PDF-file."
type: docs
url: /javascript-cpp/organize/asposepdffindhiddentext/
---

_Find hidden text in a PDF-file._

```js
function AsposePdfFindHiddenText(
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
* **textFragments** - array of :
  * text - text fragment
  * xIndent - X coordinate
  * yIndent - Y coordinate
  * fontName - font name
  * fontSize - font size


**Web Worker example**:
```js
  /*Create Web Worker*/
  const AsposePDFWebWorker = new Worker("AsposePDFforJS.js");
  AsposePDFWebWorker.onerror = evt => console.log(`Error from Web Worker: ${evt.message}`);
  AsposePDFWebWorker.onmessage = evt => document.getElementById('output').textContent = 
    (evt.data == 'ready') ? 'loaded!' :
      (evt.data.json.errorCode == 0) ? `textFragments:\n${JSON.stringify(evt.data.json.textFragments, null, 4)}` : `Error: ${evt.data.json.errorText}`; 

  /*Event handler*/
  const ffilePdfFindHiddenText = e => {
    const file_reader = new FileReader();
    file_reader.onload = event => {
      /*Find hidden text in a PDF-file - Ask Web Worker*/
      AsposePDFWebWorker.postMessage({ "operation": 'AsposePdfFindHiddenText', "params": [event.target.result, e.target.files[0].name] }, [event.target.result]);
    };
    file_reader.readAsArrayBuffer(e.target.files[0]);
  };
```

**Simple example**:
```js
  var ffilePdfFindHiddenText = function (e) {
    const file_reader = new FileReader();
    file_reader.onload = (event) => {
      /*Find hidden text in a PDF-file*/
      const json = AsposePdfFindHiddenText(event.target.result, e.target.files[0].name);
      if (json.errorCode == 0) document.getElementById('output').textContent = "JSON:\n" + JSON.stringify(json, null, 4)
      else document.getElementById('output').textContent = json.errorText;
    };
    file_reader.readAsArrayBuffer(e.target.files[0]);
  };
```
