---
title: "AsposePdfMerge2Files"
second_title: Aspose.PDF for JavaScript via C++
description:  "Merge two PDF files."
type: docs
url: /javascript-cpp/core/asposepdfmerge2files/
---

_Merge two PDF files._

```js
function AsposePdfMerge2Files(
    fileBlob1 ,
    fileBlob2 ,
    fileName1 ,
    fileName2 ,
    fileResultName 
)
```

**Parameters**: 
  * **fileBlob1** Blob object #1 
  * **fileBlob2** Blob object #2 
  * **fileName1** file name #1 
  * **fileName2** file name #2 
  * **fileResultName** result file name 

**Return**: 
JSON object 
  * **errorCode** - code error (0 no error)
  * **errorText** - text error ("" no error)
  * **fileNameResult** - result file name

**Example**:
```js
  var ffileMerge = function (e) {
    const file_reader = new FileReader();
    function readFile(index) {
      /*only two files*/
      if (index >= e.target.files.length || index >= 2) {
        /*merge two PDF-files and save the "ResultMerge.pdf"*/
        const json = AsposePdfMerge2Files(undefined, undefined, e.target.files[0].name, e.target.files[1].name, "ResultMerge.pdf");
        if (json.errorCode == 0) document.getElementById('output').textContent = json.fileNameResult;
        else document.getElementById('output').textContent = json.errorText;
        /*make a link to download the result file*/
        DownloadFile(json.fileNameResult, "application/pdf");
        return;
      }
      const file = e.target.files[index];
      file_reader.onload = function (event) {
        /*prepare(save) file from BLOB*/
        AsposePdfPrepare(event.target.result, file.name);
        readFile(index + 1)
      }
      file_reader.readAsArrayBuffer(file);
    }
    readFile(0);
  }
```
