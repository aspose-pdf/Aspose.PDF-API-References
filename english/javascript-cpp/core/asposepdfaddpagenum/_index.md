---
title: "AsposePdfAddPageNum"
second_title: Aspose.PDF for JavaScript via C++
description: "Add page number to PDF file."
type: docs
url: /javascript-cpp/core/asposepdfaddpagenum/
---

_Add page number to PDF file._

```js
function AsposePdfAddPageNum(
    fileBlob ,
    fileName ,
    fileResultName
)
```

**Parameters**: 

* **fileBlob** Blob object 
* **fileName** file name 
* **fileResultName** result file name 

**Return**: 

JSON object 

* **errorCode** - code error (0 no error)
* **errorText** - text error ("" no error)
* **fileNameResult** - result file name


**Example**:

```js
  var ffileAddPageNum = function (e) {
    const file_reader = new FileReader();
    file_reader.onload = (event) => {
      /*add page num a PDF-file and save the "ResultAddPageNum.pdf"*/
      const json = AsposePdfAddPageNum(event.target.result, e.target.files[0].name, "ResultAddPageNum.pdf");
      if (json.errorCode == 0) document.getElementById('output').textContent = json.fileNameResult;
      else document.getElementById('output').textContent = json.errorText;
      /*make a link to download the result file*/
      DownloadFile(json.fileNameResult, "application/pdf");
    };
    file_reader.readAsArrayBuffer(e.target.files[0]);
  };
```

