---
title: "function AsposePdfDecrypt"
second_title: Aspose.PDF for JavaScript via C++ API Reference
description:  "Decrypt PDF file."
type: docs
url: /javascript-cpp/main/asposepdfdecrypt/
---

## function AsposePdfDecrypt

```js
function AsposePdfDecrypt(
    fileBlob ,
    fileName ,
    password ,
    fileResultName 
)
```

**Parameters**: 

* **fileBlob** Blob object 
* **fileName** file name 
* **password** user password 
* **fileResultName** result file name 

**Return**:

JSON object

* **errorCode** - code error (0 no error)
* **errorText** - text error ("" no error)
* **fileNameResult** - result file name

_Decrypt PDF file._

**Example**:

```js
  var ffileDecrypt = function (e) {
    const file_reader = new FileReader();
    file_reader.onload = (event) => {
      /*decrypt a PDF-file with password is "owner" and save the "ResultDecrypt.pdf"*/
      const json = AsposePdfDecrypt(event.target.result, e.target.files[0].name, "owner", "ResultDecrypt.pdf");
      if (json.errorCode == 0) document.getElementById('output').textContent = json.fileNameResult;
      else document.getElementById('output').textContent = json.errorText;
      /*make a link to download the result file*/
      DownloadFile(json.fileNameResult, "application/pdf");
    };
    file_reader.readAsArrayBuffer(e.target.files[0]);
  };
```

