---
title: "AsposePdfAddImage"
second_title: Aspose.PDF for JavaScript via C++
description: "Add an image to end a PDF-file."
type: docs
url: /javascript-cpp/organize/asposepdfaddimage/
---

_Add an image to end a PDF-file._

```js
function AsposePdfAddImage(
    fileBlob,
    fileName,
    fileImage,
    fileNameResult 
)
```

**Parameters**: 

* **fileBlob** Blob object 
* **fileName** file name 
* **fileImage** image file name 
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
      (evt.data.json.errorCode == 0) ?
        `Result:\n${(evt.data.operation == 'AsposePdfPrepare') ?
          'image prepared!':
          DownloadFile(evt.data.json.fileNameResult, "application/pdf", evt.data.params[0])}` :
        `Error: ${evt.data.json.errorText}`;

  /*Set the default image filename: 'Aspose.jpg' already loaded, see settings in 'settings.json'*/
  var fileImage = "Aspose.jpg";

  /*Event handler*/
  const ffileAddImage = e => {
    const file_reader = new FileReader();
    file_reader.onload = event => {
      /*Add an image to end a PDF-file and save the "ResultImage.pdf" - Ask Web Worker*/
      AsposePDFWebWorker.postMessage(
        { "operation": 'AsposePdfAddImage',
          "params": [event.target.result, e.target.files[0].name, fileImage, "ResultImage.pdf"] },
        [event.target.result]
      );
    };
    file_reader.readAsArrayBuffer(e.target.files[0]);
  };

  const ffileImage = e => {
    const file_reader = new FileReader();
    /*Set the image filename*/
    fileImage = e.target.files[0].name;
    file_reader.onload = event => {
      /*Save the BLOB in the Memory FS for processing*/
      AsposePDFWebWorker.postMessage(
        { "operation": 'AsposePdfPrepare', "params": [event.target.result, e.target.files[0].name] },
        [event.target.result]
      );
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
  /*Set the default image filename*/
  var fileImage = "/Aspose.jpg";

  var ffileImage = function (e) {
    const file_reader = new FileReader();
    /*Set the image filename*/
    fileImage = e.target.files[0].name;
    file_reader.onload = (event) => {
      /*Save the BLOB in the Memory FS for processing*/
      AsposePdfPrepare(event.target.result, fileImage);
    };
    file_reader.readAsArrayBuffer(e.target.files[0]);
  };

  var ffileAddImage = function (e) {
    const file_reader = new FileReader();
    file_reader.onload = (event) => {
      /*Add an image to end a PDF-file and save the "ResultImage.pdf"*/
      const json = AsposePdfAddImage(event.target.result, e.target.files[0].name, fileImage, "ResultImage.pdf");
      if (json.errorCode == 0) document.getElementById('output').textContent = json.fileNameResult
      else document.getElementById('output').textContent = json.errorText;
      /*Make a link to download the result file*/
      DownloadFile(json.fileNameResult, "application/pdf");
    };
    file_reader.readAsArrayBuffer(e.target.files[0]);
  };
```
