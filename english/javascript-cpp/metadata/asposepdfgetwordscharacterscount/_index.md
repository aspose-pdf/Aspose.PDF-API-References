---
title: "AsposePdfGetWordsCharactersCount"
second_title: Aspose.PDF for JavaScript via C++
description: "Get words and characters count in a PDF-file."
type: docs
url: /javascript-cpp/metadata/asposepdfgetwordscharacterscount/
---

_Get words and characters count in a PDF-file._

```js
function AsposePdfGetWordsCharactersCount(
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
* **words** - words count
* **characters** - characters count

**Web Worker example**:
```js
  /*Create Web Worker*/
  const AsposePDFWebWorker = new Worker("AsposePDFforJS.js");
  AsposePDFWebWorker.onerror = evt => console.log(`Error from Web Worker: ${evt.message}`);
  AsposePDFWebWorker.onmessage = evt => document.getElementById('output').textContent = 
    (evt.data == 'ready') ? 'loaded!' :
      (evt.data.json.errorCode == 0) ? `\nWords count:${evt.data.json.words}\nCharacters count:${evt.data.json.characters}` : `Error: ${evt.data.json.errorText}`; 

  /*Event handler*/
  const ffilePdfGetWordsCharactersCount = e => {
    const file_reader = new FileReader();
    file_reader.onload = event => {
      /*Get words and characters count in a PDF-file - Ask Web Worker*/
      AsposePDFWebWorker.postMessage({ "operation": 'AsposePdfGetWordsCharactersCount', "params": [event.target.result, e.target.files[0].name] }, [event.target.result]);
    };
    file_reader.readAsArrayBuffer(e.target.files[0]);
  };
```
**Simple example**:
```js
  var ffilePdfGetWordsCharactersCount = function (e) {
    const file_reader = new FileReader();
    file_reader.onload = (event) => {
      /*Get words and characters count in a PDF-file*/
      const json = AsposePdfGetWordsCharactersCount(event.target.result, e.target.files[0].name);
      if (json.errorCode == 0) document.getElementById('output').textContent = "JSON:\n" + JSON.stringify(json, null, 4);
      else document.getElementById('output').textContent = json.errorText;
    };
    file_reader.readAsArrayBuffer(e.target.files[0]);
  };
```
