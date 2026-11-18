---
title: "AsposePdfVerifySigns"
second_title: Aspose.PDF for JavaScript via C++
description:  "Verify the validity of digital signatures in a PDF-file."
type: docs
url: /javascript-cpp/security/asposepdfverifysigns/
---

_Verify the validity of digital signatures in a PDF-file._

```js
function AsposePdfVerifySigns(
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
* **signs** - array of : 
  * signName - sign name
  * signStatus - status of sign : "VALID"|"INVALID"|"INACTIVE"


**Web Worker example**:
```js
  /*Create Web Worker*/
  const AsposePDFWebWorker = new Worker("AsposePDFforJS.js");
  AsposePDFWebWorker.onerror = evt => console.log(`Error from Web Worker: ${evt.message}`);
  AsposePDFWebWorker.onmessage = evt => document.getElementById('output').textContent = 
    (evt.data == 'ready') ? 'loaded!' :
      (evt.data.json.errorCode == 0) ? `signs:\n${JSON.stringify(evt.data.json.signs, null, 4)}` : `Error: ${evt.data.json.errorText}`; 

  /*Event handler*/
  const ffilePdfVerifySigns = e => {
    const file_reader = new FileReader();
    file_reader.onload = event => {
      /*Verify the validity of digital signatures in a PDF-file - Ask Web Worker*/
      AsposePDFWebWorker.postMessage({ "operation": 'AsposePdfVerifySigns', "params": [event.target.result, e.target.files[0].name] }, [event.target.result]);
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
  var ffilePdfVerifySigns = function (e) {
    const file_reader = new FileReader();
    file_reader.onload = (event) => {
      /*Verify the validity of digital signatures in a PDF-file*/
      const json = AsposePdfVerifySigns(event.target.result, e.target.files[0].name);
      if (json.errorCode == 0) document.getElementById('output').textContent = "JSON:\n" + JSON.stringify(json, null, 4)
      else document.getElementById('output').textContent = json.errorText;
    };
    file_reader.readAsArrayBuffer(e.target.files[0]);
  };
```
