---
title: "AsposePdfPrepare"
second_title: Aspose.PDF for JavaScript via C++
description:  "Save the BLOB in the Memory FS for processing."
type: docs
url: /javascript-cpp/core/asposepdfprepare/
---

_Save the BLOB in the Memory FS for processing._

```js
function AsposePdfPrepare(
    fileBlob ,
    fileName
)
```

**Parameters**: 

* **fileBlob** Blob object 
* **fileName** file name 

Aspose.PDF for JavaScript via C++ uses an internal memory file system (MemoryFS) to manipulate PDF files.

**Example**:
```js
  var ffileImage = function (e) {
    const file_reader = new FileReader();
    /*set the image filename*/
    const fileImage = e.target.files[0].name;
    file_reader.onload = (event) => {
      /*prepare(save) the image file from BLOB*/
      AsposePdfPrepare(event.target.result, fileImage);
    };
    file_reader.readAsArrayBuffer(e.target.files[0]);
  };
```

