---
title: "AsposePdfPrepareBase64"
second_title: Aspose.PDF for JavaScript via C++
description:  "Save the string representation BLOB in the Memory FS for processing."
type: docs
url: /javascript-cpp/core/asposepdfpreparebase64/
---

_Save the string representation BLOB in the Memory FS for processing._

```js
function AsposePdfPrepareBase64(
    base64Blob,
    fileName
)
```

**Parameters**: 

* **base64Blob** string representation Blob object, with format "data:mime/type;base64,...", where 'mime/type': image/png, application/octet-stream, ...
* **fileName** file name 

Aspose.PDF for JavaScript via C++ uses an internal memory file system (MemoryFS) to manipulate PDF files.

**Example**:
```js
  var ffileSignPKCS7 = function (e) {
    const test_pfx = "data:application/octet-stream;base64,MIIEcQIBAzCCBDcGCSqGSIb ... ==";
    AsposePdfPrepareBase64(test_pfx,"test.pfx");
    const file_reader = new FileReader();
    file_reader.onload = (event) => {
      /*sign a PDF-file and save the "ResultSignPKCS7.pdf"*/
      const json = AsposePdfSignPKCS7(event.target.result, e.target.files[0].name, 1, "test.pfx", "Password", 100, 100, 200, 100, "Reason", "Contact", "Location", 1, "/Aspose.jpg","ResultSignPKCS7.pdf");
      if (json.errorCode == 0) document.getElementById('output').textContent = json.fileNameResult;
      else document.getElementById('output').textContent = json.errorText;
      /*make a link to download the result file*/
      DownloadFile(json.fileNameResult, "application/pdf");
    };
    file_reader.readAsArrayBuffer(e.target.files[0]);
  };
```

