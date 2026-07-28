---
title: "AsposePdfExtractText"
second_title: "C++ 経由で JavaScript 用 Aspose.PDF"
description: "PDFファイルからテキストを抽出します。"
type: docs
url: /ja/javascript-cpp/convert/asposepdfextracttext/
---

_PDFファイルからテキストを抽出します。_

```js
function AsposePdfExtractText(
    fileBlob,
    fileName 
)
```

**Parameters**: 
  * **fileBlob** Blob object 
  * **fileName** file name 

**Return**: 
JSONオブジェクト
  * **errorCode** - code error (0 no error)
  * **errorText** - text error ("" no error)
  * **extractText** - text from PDF


**Web Worker example**:
```js
  /*Create Web Worker*/
  const AsposePDFWebWorker = new Worker("AsposePDFforJS.js");
  AsposePDFWebWorker.onerror = evt => console.log(`Error from Web Worker: ${evt.message}`);
  AsposePDFWebWorker.onmessage = evt => document.getElementById('output').textContent = 
    (evt.data == 'ready') ? 'loaded!' :
      (evt.data.json.errorCode == 0) ?
        evt.data.json.extractText :
        `Error: ${evt.data.json.errorText}`; 

  /*Event handler*/
  const ffileExtract = e => {
    const file_reader = new FileReader();
    file_reader.onload = event => {
      /*Extract text from a PDF-file - Ask Web Worker*/
      AsposePDFWebWorker.postMessage(
        { "operation": 'AsposePdfExtractText', "params": [event.target.result, e.target.files[0].name] },
        [event.target.result]
      );
    };
    file_reader.readAsArrayBuffer(e.target.files[0]);
  };
```
**Simple example**:
```js
  var ffileExtract = function (e) {
    const file_reader = new FileReader();
    file_reader.onload = (event) => {
      /*Extract text from a PDF-file*/
      const json = AsposePdfExtractText(event.target.result, e.target.files[0].name);
      if (json.errorCode == 0) document.getElementById('output').textContent = json.extractText
      else document.getElementById('output').textContent = json.errorText;
    };
    file_reader.readAsArrayBuffer(e.target.files[0]);
  };
```
