---
title: "AsposePdfAddBackgroundImage"
second_title: Aspose.PDF for JavaScript via C++
description: "Add background image to PDF file."
type: docs
url: /javascript-cpp/core/asposepdfaddbackgroundimage/
---

_Add background image to PDF file._

```js
function AsposePdfAddBackgroundImage(
    fileBlob ,
    fileName ,
    fileBackgroundImage ,
    fileResultName
)
```

**Parameters**: 

* **fileBlob** Blob object 
* **fileName** file name 
* **fileBackgroundImage** image file name 
* **fileResultName** result file name 

**Return**: 

JSON object 

* **errorCode** - code error (0 no error)
* **errorText** - text error ("" no error)
* **fileNameResult** - result file name


**Example**:

```js
  /*set the default image filename*/
  var fileBackgroundImage = "/Aspose.jpg";

  var ffileImage = function (e) {
    const file_reader = new FileReader();
    /*set the image filename*/
    fileBackgroundImage = e.target.files[0].name;
    file_reader.onload = (event) => {
      /*prepare(save) the image file from BLOB*/
      AsposePdfPrepare(event.target.result, fileBackgroundImage);
    };
    file_reader.readAsArrayBuffer(e.target.files[0]);
  };

  var ffileAddBackgroundImage = function (e) {
    const file_reader = new FileReader();
    file_reader.onload = (event) => {
      /*add a background image file a PDF-file and save the "ResultBackgroundImage.pdf"*/
      const json = AsposePdfAddBackgroundImage(event.target.result, e.target.files[0].name, fileBackgroundImage, "ResultBackgroundImage.pdf");
      if (json.errorCode == 0) document.getElementById('output').textContent = json.fileNameResult;
      else document.getElementById('output').textContent = json.errorText;
      /*make a link to download the result file*/
      DownloadFile(json.fileNameResult, "application/pdf");
    };
    file_reader.readAsArrayBuffer(e.target.files[0]);
  };
```

