---
title: "function AsposePdfAddStamp"
second_title: Aspose.PDF for JavaScript via C++ API Reference
description:  "Add stamp to PDF file."
type: docs
url: /javascript-cpp/main/asposepdfaddstamp/
---

## function AsposePdfAddStamp

```js
function AsposePdfAddStamp(
    fileBlob ,
    fileName ,
    fileStamp ,
    setBackground ,
    setXIndent ,
    setYIndent ,
    setHeight ,
    setWidth ,
    rotation ,
    setOpacity ,
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

_Add stamp to PDF file._

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
