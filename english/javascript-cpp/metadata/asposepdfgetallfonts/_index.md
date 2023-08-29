---
title: "AsposePdfGetAllFonts"
second_title: Aspose.PDF for JavaScript via C++
description: "Get list fonts from a PDF-file."
type: docs
url: /javascript-cpp/metadata/asposepdfgetallfonts/
---

_Get list fonts from a PDF-file._

```js
function AsposePdfGetAllFonts(
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
* **fonts** - array of : 
  * fontName - font name
  * isEmbedded - indicates whether the font is embedded
  * isAccessible - indicating whether the font is present


**Example**:

```js
  var ffilePdfGetAllFonts = function (e) {
    const file_reader = new FileReader();
    file_reader.onload = (event) => {
      /*Get list fonts from a PDF-file*/
      const json = AsposePdfGetAllFonts(event.target.result, e.target.files[0].name);
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
        `fonts:\n${JSON.stringify(evt.data.json.fonts, null, 4)}` :
        `Error: ${evt.data.json.errorText}`; 

  /*Event handler*/
  const ffilePdfGetAllFonts = e => {
    const file_reader = new FileReader();
    file_reader.onload = event => {
      /*Get list fonts from a PDF-file - Ask Web Worker*/
      AsposePDFWebWorker.postMessage(
        { "operation": 'AsposePdfGetAllFonts', "params": [event.target.result, e.target.files[0].name] },
        [event.target.result]
      );
    };
    file_reader.readAsArrayBuffer(e.target.files[0]);
  };
```