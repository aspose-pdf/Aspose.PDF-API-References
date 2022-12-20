---
title: "function AsposePdfSplit2Files"
description:  "Split two PDF files."
type: docs
url: /javascript-cpp/main/asposepdfsplit2files/
---

## function AsposePdfSplit2Files

```js
function AsposePdfSplit2Files(
    fileBlob ,
    fileName ,
    pageToSplit ,
    fileResultName1 ,
    fileResultName2 
)
```

**Parameters**: 
  * **fileBlob** Blob object 
  * **fileName** file name 
  * **pageToSplit** number page for split 
  * **fileResultName1** result file name #1 
  * **fileResultName2** result file name #2 

**Return**: 
JSON object 
  * **errorCode** - code error (0 no error)
  * **errorText** - text error ("" no error)
  * **fileNameResult1** - result file name #1
  * **fileNameResult2** - result file name #2

_Split two PDF files._

**Example**:
```js
  var ffileSplit = function (e) {
    const file_reader = new FileReader();
    file_reader.onload = (event) => {
      /*set number a page to split*/
      const pageToSplit = 1;
      /*split a PDF-file and save the "ResultSplit1.pdf", "ResultSplit2.pdf"*/
      const json = AsposePdfSplit2Files(event.target.result, e.target.files[0].name, pageToSplit, "ResultSplit1.pdf", "ResultSplit2.pdf");
      if (json.errorCode == 0) document.getElementById('output').textContent = e.target.files[0].name + " split: " + json.fileNameResult1 + ", " + json.fileNameResult2;
      else document.getElementById('output').textContent = json.errorText;
      /*make a link to download the first result file*/
      DownloadFile(json.fileNameResult1, "application/pdf");
      /*make a link to download the second result file*/
      DownloadFile(json.fileNameResult2, "application/pdf");
    };
    file_reader.readAsArrayBuffer(e.target.files[0]);
  };
```

