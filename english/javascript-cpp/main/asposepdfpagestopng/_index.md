---
title: "function AsposePdfPagesToPng"
second_title: Aspose.PDF for JavaScript via C++
description:  "Convert PDF file to PNG files."
type: docs
url: /javascript-cpp/main/asposepdfpagestopng/
---

_Convert PDF file to PNG files._

```
function AsposePdfPagesToPng(
    fileBlob ,
    fileName 
)
```

**Parameters**: 
  * **fileBlob** Blob object 
  * **fileName** file name 
  * **fileResultName** result file name template (for sample: "ResultPdfToPng{0:D2}.png" where {0}, {0:D2}, {0:D3}, {0:Dn} - format page number) 

**Return**: 
JSON object 
  * **errorCode** - code error (0 no error)
  * **errorText** - text error ("" no error)
  * **filesCount** - jpg files count
  * **filesNameResult** - array of result filenames



**Example**:
```js
  var ffileToPng = function (e) {
    const file_reader = new FileReader();
    file_reader.onload = (event) => {
      /*convert a PDF file to png-files with template "ResultPdfToPng{0:D2}.png" ({0}, {0:D2}, {0:D3}, ... format page number) and save*/
      const json = AsposePdfPagesToPng(event.target.result, e.target.files[0].name, "ResultPdfToPng{0:D2}.png");
      if (json.errorCode == 0) {
        document.getElementById('output').textContent = "Files(pages) count: " + json.filesCount.toString();
        /*make links to result files*/
        for (let fileIndex = 0; fileIndex < json.filesCount; fileIndex++) DownloadFile(json.filesNameResult[fileIndex], "image/png");
      }
      else document.getElementById('output').textContent = json.errorText;
    };
    file_reader.readAsArrayBuffer(e.target.files[0]);
  };
```
