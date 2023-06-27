---
title: "AsposePdfAddStamp"
second_title: Aspose.PDF for JavaScript via C++
description: "Add stamp to PDF file."
type: docs
url: /javascript-cpp/core/asposepdfaddstamp/
---

_Add stamp to PDF file._

```js
function AsposePdfAddStamp(
    fileBlob,
    fileName,
    fileStamp,
    setBackground,
    setXIndent,
    setYIndent,
    setHeight,
    setWidth,
    rotation,
    setOpacity,
    fileNameResult 
)
```

**Parameters**:

* **fileBlob** Blob object
* **fileName** file name 
* **fileStamp** stamp (image) file name 
* **setBackground** background (1 or 0) 
* **setXIndent** x indent stamp 
* **setYIndent** y indent stamp 
* **setHeight** height stamp 
* **setWidth** width stamp 
* **rotation** stamp rotation:
  * Module.Rotation.None
  * Module.Rotation.on90
  * Module.Rotation.on180
  * Module.Rotation.on270 
* **setOpacity** opacity stamp (decimal) 
* **fileResultName** result file name 

**Return**:

JSON object

* **errorCode** - code error (0 no error)
* **errorText** - text error ("" no error)
* **fileNameResult** - result file name

**Example**:

```js
  /*set the default stamp filename*/
  var fileStamp = "/Aspose.jpg";

  var ffileStamp = function (e) {
    const file_reader = new FileReader();
    /*set the stamp filename*/
    fileStamp = e.target.files[0].name;
    file_reader.onload = (event) => {
      /*prepare(save) the stamp file from BLOB*/
      AsposePdfPrepare(event.target.result, fileStamp);
    };
    file_reader.readAsArrayBuffer(e.target.files[0]);
  };

  var ffileAddStamp = function (e) {
    const file_reader = new FileReader();
    file_reader.onload = (event) => {
      /*insert the stamp file to a PDF-file and save the "ResultImage.pdf"*/
      const json = AsposePdfAddStamp(event.target.result, e.target.files[0].name, fileStamp, 0, 5, 5, 40, 40, Module.Rotation.on270, 0.5, "ResultStamp.pdf");
      if (json.errorCode == 0) document.getElementById('output').textContent = json.fileNameResult;
      else document.getElementById('output').textContent = json.errorText;
      /*make a link to download the result file*/
      DownloadFile(json.fileNameResult, "application/pdf");
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
        `Result:\n${(evt.data.operation == 'AsposePdfPrepare') ?
          'image prepared!':
          DownloadFile(evt.data.json.fileNameResult, "application/pdf", evt.data.params[0])}` :
        `Error: ${evt.data.json.errorText}`;

  /*set the default stamp filename: 'Aspose.jpg' already loaded, see settings in 'settings.json'*/
  var fileStamp = "Aspose.jpg";

  /*Event handler*/
  const ffileAddStamp = e => {
    const file_reader = new FileReader();
    file_reader.onload = event => {
      const setBackground = 0;
      const setXIndent_ = 5;
      const setYIndent_ = 5;
      const setHeight_ = 40;
      const setWidth_ = 40;
      const rotation_ = 'Module.Rotation.on270';
      const setOpacity = 0.5;
      /*insert the stamp file to a PDF-file and save the "ResultStamp.pdf" - Ask Web Worker*/
      AsposePDFWebWorker.postMessage(
        { "operation": 'AsposePdfAddStamp',
          "params": [event.target.result, e.target.files[0].name, fileStamp, setBackground, setXIndent_, setYIndent_,
                     setHeight_, setWidth_, rotation_, setOpacity, "ResultStamp.pdf"] },
        [event.target.result]
      );
    };
    file_reader.readAsArrayBuffer(e.target.files[0]);
  };

  const ffileStamp = e => {
    const file_reader = new FileReader();
    /*set the stamp filename*/
    fileStamp = e.target.files[0].name;
    file_reader.onload = event => {
      /*prepare(save) the stamp file from BLOB*/
      AsposePDFWebWorker.postMessage(
          { "operation": 'AsposePdfPrepare', "params": [event.target.result, e.target.files[0].name] },
          [event.target.result]
      );
    };
    file_reader.readAsArrayBuffer(e.target.files[0]);
  };

  /*make a link to download the result file*/
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