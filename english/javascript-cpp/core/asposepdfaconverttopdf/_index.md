---
title: "AsposePdfAConvertToPDF"
second_title: Aspose.PDF for JavaScript via C++
description:  "Convert a PDF/A-file to PDF."
type: docs
url: /javascript-cpp/core/asposepdfaconverttopdf/
---

_Convert a PDF/A-file to PDF._

```js
function AsposePdfAConvertToPDF(
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
  var ffilePdfAConvertToPDF = function (e) {
    const file_reader = new FileReader();
    file_reader.onload = (event) => {
      /*convert a PDF/A-file to PDF and save the "ResultConvertToPDF.pdf"*/
      const json = AsposePdfAConvertToPDF(event.target.result, e.target.files[0].name, "ResultConvertToPDF.pdf");
      if (json.errorCode == 0) document.getElementById('output').textContent = json.fileNameResult;
      else document.getElementById('output').textContent = json.errorText;
      /*make a link to download the result file*/
      DownloadFile(json.fileNameResult, "application/pdf");
    };
    file_reader.readAsArrayBuffer(e.target.files[0]);
  };
```

